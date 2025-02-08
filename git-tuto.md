# Git Commands

![Git-Archetecture](Git-Architecture.png)

## Git Basic Configuration (done only one time after installation)
```bat
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

## Initialize the current folder as a local repository
git init

## Connect the local repository to the remote one
git remote add origin <remote_repository_url>

## Clone the remote repository inside a folder named the same as the repository name
git clone <remote_repository_url>

## Add files from the working directory to the staging area
git add .
git add <file_name>
git add <folder_name>

## Check out the files currently in and not in the staging area
git status

## Save all the files contained in the staging area to the local repository
git commit -m "Commit Message"

## Display the history of commits
git log

## Push the content of the local repository to the remote one 
git push origin [<remote_branch_name>]

## Pull the content from the remote repository to the local one
git pull