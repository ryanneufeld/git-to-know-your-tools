# Git to know your tools
- Ryan Neufeld
- @ryanneufeld
- ryanneufeld on freenode

# What is git anyway?
## What is a 'repo'
- A place where things are stored.
    + On your computer
    + On someone elses computer (github, bitbucket, stash)
- In context
    + A directory containing Zero or more files.
    + Contents are versioned.
    + Old versions can be compared and or retrieved.


# Distributed vs centralized vcs
## Disributed
- git
- mercurial
- bazzar (no one uses this, and you can't too)

## Centralized
- perforce
- svn
- cvs


# Terminology
- Git is not Github
- Github is a git repository host
- So is Bitbucket.

# Three trees (areas or lists):
- Working
    + This is your copy of the code. This is what you edit.
- Stage
    + This is where your changes go when you `git add` them.
- Index
    + This is where your changes go when you `git commit`.

# git config
## git config --global vs local
## Setting up your editor


# git init


# git clone
- Make a copy of someone else's repository
    + via ssh
    + file path
    + via http



# git add
- Add changes from Working tree, to the stage tree.
## git add -p
- Add partial files to from the working tree to the stage tree.

# git commit
- Add changes in the stage tree to the index.
- --amend to change the last commit messgae

# git checkout
## git checkout -b
## git branch
## detached head


# git log
## git 

# git reset
## Reset your working directory to a previous state
- --hard
    + Discards all (un-)staged changes.
- --soft
    + Leaves changes staged.



# git pull/push/fetch

# git rebase
- there be dragons here.

# git reflog
- now you're screwed, what do you do?

# git bisect, grep

## Ignore certain patches
- Git can let you make changes, say to a db config, and then ignore the changes you've made, such as db username/password


# Notes:
- Provide any needed configs rather than have them type them out.



[1]http://rogerdudler.github.io/git-guide/
[2]