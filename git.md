# Git

Git is an open source distributed version control system that enables collaborative tracking of changes in source code during software development.

## Create & fetch

| Command           | Description                                                            |
| ----------------- | ---------------------------------------------------------------------- |
| `git init`        | Initialize the current working directory as a new local git repository |
| `git clone <url>` | Clone a remote repository to your local client                         |

## Snapshot

A snapshot represents the state of something, a copy of a project at a specific point in time.

| Command                   | Description                                                                                                             |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `git status`              | Shows uncommitted changes, new files etc.                                                                               |
| `git add <file>`          | Add and stage a new file for the next commit.                                                                           |
| `git rm <file>`           | Remove a file and stage the deletion for the next commit                                                                |
| `git rm --cached <file>`  | Stage files for removal only from the index and show them untracked. It doesn't remove files from the working directory |
| `git add .`               | Add and stage all changes in the current working directory for the next commit                                          |
| `git commit -m "message"` | Commit staged changes under a new commit                                                                                |
| `git commit`              | Opens an editor to write more descriptive change messages                                                               |
|                           |                                                                                                                         |

## Branch & Merge

| Command                  | Description                                               |
| ------------------------ | --------------------------------------------------------- |
| `git branch `            | Shows a list of existing branches                         |
| `git branch -a`          | List of all local and remote branches                     |
| `git branch <branch>`    | Creates a new branch based on the currently active branch |
| `git checkout <branch> ` | Switch to another branch                                  |
| `git merge <branch>`     | Merge a selected branch into the active branch            |
## Share & Update

| Command                     | Description                                                             |
| --------------------------- | ----------------------------------------------------------------------- |
| `git push `                 | Push committed changes to remote repository                             |
| `git push origin <branch> ` | Push local branch changes to remote branch of a different name          |
| `git pull`                  | Pull the latest changes from the remote repository into your local repo |

## Inspect & Compare

| Command                    | Description                                            |
| -------------------------- | ------------------------------------------------------ |
| `git log`                  | Lists the chronological history of commits             |
| `git log --pretty=oneline` | Lists the chronological history of commits in one line |
