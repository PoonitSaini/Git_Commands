# Git Configuration 
1. git config --global user.name "My Name" # To configure user name 
2. git config --global user.email "exmaple@gmail.com" # To configure Email
3. git config --list # To check what is configured 
4. git --version # To Cheack Git Version 
# Clone & Status 
1. git clone <-Link-> # To Clone the Repository
2. git status # To Check State of Code

# Add & Commit 
1. git add <-file-> # To Add Changes in File
2. git commit -m <-Comment-> # To Commit Changes in File

# Push Command 
1. git push origin main # To make changes in Github main Branch
2. git push origin <-branch-> # To make changes in Github Branch 
2. git push -u origin main # To make changes in Github Branch and make a Shoutcut for next time (use git push)

# Pull Command 
1. git pull origin main # To Fetch Remote Repo and Immediately Update Local repo to Match That Content
2. git pull origin <-branch-> # To Fetch Remote Repo and Immediately Update Local repo to Match That Content

# Init Command 
1. git init # To Create a New Git Repo
2. git remote add origin <-link-> # To Add New Remote Repo
3. git remote -v # To Verify Remote Repo

# Branch Command 
1. git branch # To Cheak Repo Branch 
2. git branch -m main # To rename Current Branch
3. git checkout <-branch name-> # To Change Branch
4. git checkout -b <-new branch name-> # To Create New Branch
5. git branch -d <-branch name-> # To Delete Branch

# Merging Code 
1. git diff <-branch name-> # To Compare Commits,Branch,Files & More
2. git merge <-branch name-> # To Merge Two Branches

# Undoing Changes
1. git reset <-file name-> # Reset Staged Changes in Specific File
2. git reset # Reset Staged Changes in All Files
3. git reset head~1 # Reset Commited Changes for one Commit
4. git reset <-Commit hash-> # Reset Commited Chnages for many Commit or Specific Commit
5. git reset --hard <-commit hash-> # Reset Commited Changes in local also  
6. git log # To Get All Commits Hash (use Q to Exit)

# Some Other Important Commands 
1. cd <-DirectoryName-> # To Change Directory
3. cd .. # To Exit Directory
4. mkdir <-Directory Name-> # To Add New Folder in Local 
5. ls # To Check all files in Directory 
6. ls -force # To check Hidden Files
