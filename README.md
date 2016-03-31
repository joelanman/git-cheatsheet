# Git Cheatsheet

## Introduction

Git is a system to save versions of your project. If you work on your project with other people, Git keeps you all up to date with each other's work.

You use Git in the Terminal (Mac) or in [Git Bash](https://git-scm.com/downloads) (Windows).

You need to change to your project directory (using the `cd` command) before running any Git command.

Some terms:

- **Repository** or 'repo' is your project stored by Git, with all your changes recorded so you can undo them.
- **Commit** a saved version of your project

## 1. Working on files on your own computer

`git init`

Run this to start using Git on a new project.
You don't need to do this if you downloaded an existing repository.

`git status`

Tells you if you have any new files, or files that have changed.

`git add -A`

Add any new files to Git, remove any deleted files from Git. -A means All.

`git commit -am "[Your commit message]"`

Commit your changes to Git - like saving a version of your project.

`git log`

Show a list of commits - your commit messages appear here. Press 'q' to quit or press space to see more.
