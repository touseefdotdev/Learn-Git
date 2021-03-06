# Learn Git

![Git Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png)

## What is Git?
Git is free and open-source version control system. A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. As developers make changes to the project, any earlier version of the project can be recovered at any time.

Developers can review project history to find out:
- Which changes were made?
- Who made the changes?
- When were the changes made?
- Why were changes needed?

## About repositories
A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file's revision history. 
- The file history appears as snapshots in time called commits. 
- The commits can be organized into multiple lines of development called branches. 
Because Git is a DVCS, repositories are self-contained units and anyone who has a copy of the repository can access the entire codebase and its history. 

Using the command line or other ease-of-use interfaces, a Git repository also allows for: interaction with the history, cloning the repository, creating branches, committing, merging, comparing changes across versions of code, and more.

Through platforms like GitHub, Git also provides more opportunities for project transparency and collaboration. Public repositories help teams work together to build the best possible final product.

## Git commands

### Git: Configurations

(global settings)
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"
- git config --global color.ui true
- git config --list

(local/repo settings)
- git config user.email "you@gmail.com"
- git config user.name "Your Name"

### Git: Starting a Repo
- git init \[repo name]
- git clone \[cloning-address-of-remote-repo]
- git status

### Git: Staging files
- git add \[file name[s]]
- git add .
- git add --all
- git add -A
- git rm --cached \[file name]
- git reset \[file name]

### Git: Commiting to a repo
- git commit -m "\[title]" -m "\[description]"
- git reset
- git reset --soft HEAD^
- git commit --amend -m "enter your message"

### Git: Other useful commands

- git push origin main
- git branch \[branch name] OR git -b checkout \[branch name]
- git checkout \[branch name]
- git remote
- git pull
- git merge \[branch name]
- git diff
- git revert
- git tag
- git log

To connect your Git with your GitHub account;
- ssh-keygen -t ed25519 -C "your_email@example.com" OR ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- ssh-add \[key location i.e. ~/.ssh/key]


https://rubygarage.s3.amazonaws.com/uploads/article_image/file/599/git-cheatsheet-5.jpg
