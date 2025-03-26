# Git Commands - Basic Guide

## Setup
```sh
# Set user name
git config --global user.name "Your Name"

# Set user email
git config --global user.email "your.email@example.com"
```

## Repository Initialization
```sh
# Initialize a new repository
git init
```

## Cloning a Repository
```sh
# Clone an existing repository
git clone <repository-url>
```

## Basic Workflow
```sh
# Check repository status
git status

# Add files to staging area
git add <file>  # Add a specific file
git add .       # Add all changes

# Commit changes
git commit -m "Commit message"

# Push changes to remote repository
git push origin <branch>
```

## Branching
```sh
# List branches
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>

# Create and switch to a new branch
git checkout -b <branch-name>
```

## Merging
```sh
# Merge a branch into the current branch
git merge <branch-name>
```

## Pulling Changes
```sh
# Get latest changes from remote repository
git pull origin <branch>
```

## Undoing Changes
```sh
# Undo changes in a file (unstaged)
git checkout -- <file>

# Unstage a file
git reset <file>

# Undo the last commit (keep changes)
git reset --soft HEAD~1

# Undo the last commit (discard changes)
git reset --hard HEAD~1
```

## Viewing History
```sh
# View commit history
git log

# View commit history in one line
git log --oneline
```

## Remote Repository
```sh
# Add a remote repository
git remote add origin <repository-url>

# Show remote repositories
git remote -v
```

## Stashing Changes
```sh
# Save changes temporarily
git stash

# Apply the latest stash
git stash pop

# List all stashes
git stash list
```

