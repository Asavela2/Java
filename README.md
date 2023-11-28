# Git
Git is a version control system for tracking changes in computer files.
It helps in coordinating work amongst several people in a project and tracks progress over time. 
Unlike the centralized version control system, Git branches can be easily merged.

## Git tools

Git is a powerful distributed version control system widely used for source code management and collaboration. 
There are several tools and commands available to interact with Git. Here are some essential Git tools and commands:

git init:


Initializes a new Git repository.
```
git init
```
git clone:

Creates a copy of a remote repository on your local machine.
```
git clone <repository_url>
```
git add:
Adds changes in the working directory to the staging area.

```
git add <file_name>
```
git commit:
Records changes in the repository.
```
git commit -m "Commit message"
```
git status:
Shows the status of changes as untracked, modified, or staged.
```
git status
```
git pull:
Fetches changes from a remote repository and merges them into the current branch.
```
git pull
```
git push:
Pushes local changes to a remote repository.
```
git push
```
git branch:
Lists existing branches or creates a new branch.
```
git branch
git branch <branch_name>
```
git checkout:
Switches between branches or restores working tree files.
```
git checkout <branch_name>
```
git merge:
Merges changes from one branch into another.
```
git merge <branch_name>
```
git log:
Displays the commit history.
```
git log
```
git diff:
Shows changes between commits, branches, or the working directory.
```
git diff
```
git remote:
Shows a list of remote repositories.
```
git remote -v
```
git fetch:
Downloads objects and refs from another repository.
```
git fetch
```
git reset:
Resets the current branch to a specific commit.
```
git reset --hard <commit_hash>
```
git stash:
Temporarily saves changes that are not ready to be committed.
```
git stash
```
git tag:
Creates, lists, or deletes tags.
```
git tag -a <tag_name> -m "Tag message"
```
