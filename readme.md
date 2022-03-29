# Git Cheatsheet

## git repository

- `git init` - Initialize a new git repository in the current directory
- `git status` - show the status of the git repository

## commit

- `git add` - adds a file to the current stage
- `git commit -m <commit message>` - commits all changes from the current stage
- `git log` - displays a log of the commits

## how to return to save points

- `git restore <file name>` - restores a file from the newest commit
- `git restore --staged <file name>` - restores a staged file 

## remote repository

- `git remote add origin <ssh link>` - sets the remote target `<origin>` to `<ssh link>`
- `git remote -v` - displays all remote targets
- `git push -u origin <branch name>` - links the remote target `<origin>` to `<branch name>` and pushes the committed changes to the remote target
- `git push` pushes the committed changes to the linked remote target
- `git pull -u origin <branch name>` - links the remote target `<origin>` to `<branch name>` and pulls all changes from the remote target
- `git pull` - pulls all changes from the linked remote target

## branching

- `git branch` - displays all branches 
- `git branch <branch name>` - creates a new branch with `<branch name>`
- `git switch <branch name>` - switches to the branch `<branch name>` 

