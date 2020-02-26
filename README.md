z# Command Line Definitions

## cd - change directory

## ls - list directory contents

## ls -a - shows visible and hidden files/directories

## man <command> - displays manual for given command

## mkdir <directory name> - make directory with given name

## pwd - print working directory

## touch <filename> - create file with given name

## cd .. - move up a directory

## cd ~ - home

# Git Definitions

## git init - initialize an empty repository

## git add <filename> - moves a modified file to the staging area

## git commit -m "<message>" - moves staged files to the Git Directory and labels the commit with a message for other/future developers

## git config --global user.name = change or set global username

## git config --global user.email = change or set global email address

## git config --global --list = dispays global settings

## git config --global core.editor <editor of choice> = set your global editor (nano)

## git commit --amend -m "<new message>" = changes the commit message of the last commit to the new message provide

## git checkout-- <filename> = removes any changes made to the file in working directory and reverts its status back from mod to unmod. (undoing changes made to file)

## git reset HEAD <filename> = moves the staged file from the Staging Area to the Working directory

## git branch <branchname> = create a new branch with the given name

## git checkout <branchname> = switch to new branch

## git checkout -b <branchname> = create new branch and switch to it

## git branch -d <branchname> = delete existing branch with given name

## git branch -m <oldname> <newname> = changes branch name

## git merge <branchname> = merges the histories of two branches onto the alpha branch

## git branch = lists all branches and the one you're currently on

## git rebase = keeps history clean, moves history onto another branch (only use if you have been working locally not on a remote repository.)

## Merge Steps
1. checkout the branch we want to merge changes into.
2. git merge <branchWithChanges>

boom shakalaka
