# Git-Cheat-Sheet
# git-cheat-sheet

## Configuring Git
- Set up user name: `git config --global user.name "Your Name"`
- Set up email: `git config --global user.email "your.email@example.com"`
- Set up default text editor: `git config --global core.editor "nano"`

## Basic Commands
- Initialize a repository: `git init`
- Clone a repository: `git clone <repository-url>`
- Check status: `git status`
- Add files to staging area: `git add <file>`
- Commit changes: `git commit -m "Commit message"`
- Push changes to remote repository: `git push`
- Pull changes from remote repository: `git pull`

## Branching and Merging
- Create a new branch: `git branch <branch-name>`
- Switch to a branch: `git checkout <branch-name>`
- Create and switch to a new branch: `git checkout -b <branch-name>`
- Merge branches: `git merge <branch-name>`

## Viewing and Undoing Changes
- View changes: `git diff`
- Undo unstaged changes: `git checkout -- <file>`
- Undo last commit (keep changes): `git reset HEAD~`
- Undo last commit (discard changes): `git reset --hard HEAD~`

## Remote Repositories
- Add a remote repository: `git remote add <remote-name> <repository-url>`
- View remote repositories: `git remote -v`
- Remove a remote repository: `git remote rm <remote-name>`

