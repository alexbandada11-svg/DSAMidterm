**Name:**  Bandada, Alexander H.  
**Section:** BSCpE 1-1

## How to Set up Git and GitHub


1. Go to https://git-scm.com/.  
2. Download and Install Git based on your OS.  
3. Create a file and right-click to verify if Git is properly installed (*If Git Bash appears, it means that it is properly installed*).  
4. Create a dummy file.  
5. Open the command prompt by typing "cmd".  
6. Open visual studio code by typing "code ." (*Make sure that VSCode is already downloaded and installed in your device*).  
7. Go to terminal and switch to command prompt.  
8. Turn on Autosave and Download the "Convetional Commits" Extension.  
9. Create a new file "helloWorld.html" (*The file should also appear in the folder that is previously created*).  
10. Create an account in https://github.com and use this account in Git.  
11. Create a public respository in GitHub.  
12. Copy the following from codemy and type it in Git Bash:  

  git config --global user.name "Your Name"  
  git config --global user.email "you@youraddress.com"  
  git config --global push.default matching  
  git config --global alias.co checkout
  git init  

13. Create "README.md" file and type the following on the commad line:

  git init  
  git add README.md  
  git commit -m "first commit"  
  git branch -M main  
  git remote add origin https://github.com/Desktop/Bandada,Alexander_DSAMidterms  
  git push -u origin main  

14. Create an HTML file (*Anything typed in the HTML file should be synced in the folder that is created previously*).  

## Commit and Push Changes to GitHub

1. Go to Source Control.  
2. Stage Changes by pressing "+".  
3. Commit changes by pressing "o".  
4. Sync changes and referesh GitHub.  
5. If done correctly, all changes should be synced in your GitHub. 

### To clone your repository to other devices.

1. Click the code dropdown on GitHub.  
2. Copy URL  
3. On your other device, create a new folder.  
4. Right-click on the folder and click Git Bash.  
5. type "$ git clone" and paste the URL.  
6. If done correctly, the clone should be accurate to your original repository.  