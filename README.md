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

# SDLC (Software Development Life Cycle)

The Software Development Life Cycle (SDLC) is a systematic process for planning, creating, testing, deploying, and maintaining software. 
It outlines the steps involved in the development of software and serves as a roadmap for the entire development process.
There are several SDLC models, and each model has its own set of advantages and disadvantages. 

- Here are some of the commonly used SDLC models:

## Waterfall Model:

- Sequential and linear approach.
- Progress is seen as flowing steadily downwards through phases such as Requirements, Design, Implementation, Testing, Deployment, and Maintenance.
- Each phase must be completed before the next one begins.
   
# Iterative Model:

- Development is broken down into smaller cycles or iterations.
- Each iteration goes through the phases of the SDLC, with the possibility of revisiting and making changes based on feedback.
- It allows for flexibility and incremental development.
  
# Agile Model:

- Emphasizes iterative and incremental development.
- Prioritizes collaboration and customer feedback.
- Development is carried out in small, rapid cycles called sprints.
- Changes can be made at any point in the development process.
  
# V-Model (Verification and Validation):

- Extension of the waterfall model.
- Each development stage has a corresponding testing phase.
- Testing is integrated into each phase of development.
  
# Spiral Model:

- Combines elements of both waterfall and iterative models.
- Focuses on risk assessment and allows for changes to be made as the project progresses.
- Development proceeds in a spiral fashion, with repeated cycles.
  
# Big Bang Model:

- No specific process is followed, and development begins with little planning.
- Developers start coding without a clear understanding of requirements.
- Suitable for small projects with changing requirements.
  
# Prototyping Model:

- A prototype (a preliminary version of the software) is built based on initial requirements.
- The prototype is used for feedback and refinement.
- The final system is developed based on the approved prototype.
  
# Incremental Model:

- Divides the system functionality into small, manageable modules or increments.
- Each increment adds new functionality to the system.
- The software is developed, integrated, and tested incrementally.
  
# RAD Model (Rapid Application Development):

- Emphasizes quick development and iteration.
- Involves user feedback and iteration in a fast-paced development cycle.
- Suitable for projects with short development cycles.

