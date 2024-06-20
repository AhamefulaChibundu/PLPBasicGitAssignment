# PLPBasicGitAssignment

### How to create a repo and link it to your local computer

These are the steps i followed to create a repo and initialize it:
    1. Logged in to my GitHub account, created a repository and added a README file while creating the repo. I named the repo "PLPBasicGitAssignment"

    2. I Created a new folder on your local machine and named it "PlpBasicGit" and then i opened my gitbash and navigated to the newly created folder.

    3. I Initialized a new Git repository in my local folder using the command "git init"

    4. Linked my local repository to the GitHub repository I created. I did this by using "git remote add origin <repository-url>" (git remote add origin https://github.com/AhamefulaChibundu/PLPBasicGitAssignment.git)

    5. Inside my local folder, I created a new text file named `hello.txt` and added a text "Hello Git!"

    6. I saved the changes by using "Git add hello.txt" and committed by using " git commit -m 'Add hello.txt with a greeting'"

    7. The last step is to push the changes to Github using the command "git push -u origin main". I tried this command but i was having the error "error: failed to push some refs to 'https://github.com/AhamefulaChibundu/PLPBasicGitAssignment.git'
    hint: Updates were rejected because the remote contains work that you do not
    hint: have locally. This is usually caused by another repository pushing to
    hint: the same ref. If you want to integrate the remote changes, use
    hint: 'git pull' before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details."

    This error kept occouring because I added a README file while creating the repo and my local machine was not aware of that initial commit. To resolve this error, I used the command "git pull --rebase origin main". this command pulled the README file to my local machine, then I used the "git push -u origin main" command and the changes were pushed to Github.