# Git Commands Cheat Sheet

This repository is designed to help you get familiar with basic Git commands for version control.

## Basic Commands

- **`git init`**  
  Initializes a new Git repository in the current directory.

- **`git add .`**  
  Stages all changed files, preparing them for commit.

- **`git commit -m "commit message"`**  
  Commits the staged changes with a descriptive commit message.

- **`git status`**  
  Displays the current status of your working directory and staging area.
  - Use `git add <file>` to update what will be committed.
  - Use `git restore <file>` to discard changes in the working directory.

- **`git log`**  
  Shows a log of all commits in the current branch.

- **`git diff`**  
  Shows the differences between the working directory and the last commit.

- **`git restore <file>`**  
  Reverts changes in a specified file (e.g., `git restore index.html`).

## Working with Branches

- **`git branch`**  
  Lists all branches and highlights the current branch.

- **`git checkout -b <branch-name>`**  
  Creates a new branch and switches to it.

- **`git checkout <branch-name>`**  
  Switches to an existing branch.

- **`git merge <branch-name>`**  
  Merges changes from the specified branch into the current branch.

## Remote Repositories

- **`git remote add origin <repository-url>`**  
  Adds a remote repository to your local Git configuration.

- **`git push origin <branch-name>`**  
  Pushes changes from your local branch to the remote repository.

- **`git pull origin <branch-name>`**  
  Pulls the latest changes from the remote branch to your local machine.

## Fetch vs Pull

- **`git pull`**:  
  A combination of `git fetch` and `git merge`. It fetches updates from the remote repository and immediately merges them into the current branch.

- **`git fetch`**:  
  Downloads updates from the remote repository but does not merge them or modify the current branch. It only updates the remote tracking branches.

By using these commands, you'll be able to manage your Git repositories effectively, track changes, and collaborate with others.