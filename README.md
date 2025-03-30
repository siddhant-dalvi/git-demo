

# 1. Git Clone
## Creates a local copy of a remote repository
echo "Cloning repository..."<br>
`git clone <repository-url>`

# 2. Git Branch
## Creates, lists, or deletes branches
echo "Creating a new branch..."<br>
`git branch <branch-name>` <br>
echo "Listing all branches..."<br>
`git branch --list`  
echo "Deleting a branch..."<br>
`git branch -d <branch-name>` 

# 3. Git Checkout
## Switches to a different branch or creates a new one
echo "Switching to an existing branch..."<br>
`git checkout <branch-name>`  
echo "Creating and switching to a new branch..."<br>
`git checkout -b <branch-name>` 

# 4. Git Status
## Shows the current status of the working directory and staging area
echo "Checking the status of files..."<br>
`git status` 

# 5. Git Add
## Stages changes to be committed
echo "Staging a specific file..."<br>
`git add <file>`  
echo "Staging all changes..."<br>
`git add -A`  

# 6. Git Commit
## Records changes to the local repository
echo "Committing changes..."<br>
`git commit -m "commit message"`  

# 7. Git Push
## Uploads committed changes to the remote repository
echo "Pushing changes to the remote repository..."<br>
`git push <remote> <branch-name>` 

# 8. Git Pull
## Fetches and merges updates from the remote repository
echo "Pulling changes from the remote repository..."<br>
`git pull <remote>` 

# 9. Git Revert
## Reverts a specific commit by creating a new commit that undoes the changes
echo "Reverting a commit..."<br>
`git revert <commit-hash>`

# 10. Git Merge
## Merges changes from one branch into another
echo "Switching to the target branch..."<br>
`git checkout <target-branch>`<br> 
echo "Merging changes from the feature branch..."<br>
`git merge <branch-name>`  

