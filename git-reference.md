# Git Command Reference

This file contains Git commands that I can use to manage my programming projects and track changes throughout the course.

## Repository Setup

| Command | Purpose |
|---|---|
| `git init` | Creates a new Git repository. |
| `git clone <repository-url>` | Copies an existing repository to my computer. |
| `git status` | Shows the current state of my working directory. |
| `git remote -v` | Displays connected remote repositories. |

## Tracking Changes

| Command | Purpose |
|---|---|
| `git add .` | Stages changes in the current directory. |
| `git add <file>` | Stages a specific file. |
| `git diff` | Shows changes that have not been staged. |
| `git diff --staged` | Shows changes that have been staged. |

## Saving Changes

| Command | Purpose |
|---|---|
| `git commit -m "message"` | Saves staged changes as a commit. |
| `git log --oneline` | Displays a short history of commits. |
| `git show` | Displays information about a commit. |

## Working with GitHub

| Command | Purpose |
|---|---|
| `git push` | Uploads local commits to GitHub. |
| `git pull` | Downloads and integrates changes from the remote repository. |

## My Typical Git Workflow

1. Use `git status` to check for changes.
2. Make changes to my project files.
3. Use `git add .` to stage the changes.
4. Use `git diff --staged` to review staged changes.
5. Use `git commit -m "Describe the changes"` to save a commit.
6. Use `git push` to upload my commits to GitHub.

I will use this reference to help manage my projects and maintain an organized development history throughout the course.