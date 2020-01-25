# Git Kata: 3-Way Merge

## Setup

1. Run `. setup.sh` (or `.\setup.ps1` in PowerShell)

## The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.

1. Create a branch called greeting and check it out
2. Edit the greeting.txt to contain your favorite greeting
3. Add greeting.txt files to the staging area
4. Commit
5. Switch back to the master branch
6. Create a file README.md with information about this repository
7. Add the README.md file to staging area and make the commit
8. What is the output of `git log --oneline --graph --all`?
9. Diff the branches
10. Merge the greeting branch into master

## Useful commands
- `git branch`
- `git branch <branch-name>`
- `git branch -d <branch-name>`
- `git checkout <branch-name>`
- `git checkout -b <branch-name>`
- `git branch -v`
- `git add`
- `git commit`
- `git commit -m`
- `git merge <branchA> <branchB>`
- `git diff <branchA> <branchB>`
- `git log --oneline --graph --all`

## Answers:
## What is the output of git log --oneline --graph --all?
## C:\Users\Raiki\Documents\GitHub\191-Jeimeil-Rey-Rosal-Mercado>git log
##commit 9936afe693d0c96b5c6f970646c999188ea3ba1c (HEAD -> master, origin/master)
##Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
##Date:   Fri Jan 24 18:18:09 2020 -0800

##    Create README.md

##commit 1a2f9c4d12c8a7c2b7c5f7d33dd1861b4ac57e76
##Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
##Date:   Fri Jan 24 18:13:37 2020 -0800

##    Katas