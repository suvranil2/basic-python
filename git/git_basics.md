# Git Basics
## Date: 22nd April, 2022

**Here We will learn to clone a repository from Github to our local machine** <br/>

Step 01: Copy the HTTPS of that repo. <br/>
Step 02: Open your terminal. Then write command: <br/>
*git clone https://github.com/suvranil2/demo-repo.git* <br/>

**Check the changes** <br/>
use the command: git status <br/>

It will show all the changes (added/deleted) you have done but have not commited yet. <br />

Sometimes we add new files. To track those files, use the command: git add .
It means git will track all untracked files in your folder. 

**Change file in GitHub from your local repo** <br/>
Command: git push

**Undoing in git** <br />
Command: git reset  <br />
To undo commit, command: git reset HEAD~1 (Head means commit message and ~1 means delete last commit)

**Check difference** <br />
Command: git diff

**Check all commits** <br />
Command: git log


