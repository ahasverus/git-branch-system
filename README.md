# git-branch

This repository is dedicated to show how to deal with the [`git branch system`](https://www.atlassian.com/git/tutorials/using-branches).

Main commands:

```sh
## Print git history ----
git log --graph --decorate --oneline

## List git local branches ----
git branch

## Create a new local branch and switch to it ----
git checkout -b improve-documentation

## List git local branches ----
git branch

## Switch to main branch ----
git checkout main

## Switch to new branch ----
git checkout improve-documentation

## Stage and commit ----
#  ...

## Push new branch to GitHub ----
git push --set-upstream origin improve-documentation

## List all git branches (remote included) ----
git branch -a

## Merge new branch into main ----
git checkout main
git merge improve-documentation

## Delete a local branch ----
git branch -d improve-documentation

## List git local branches ----
git branch

## List all git branches (remote included) ----
git branch -a

## Delete remote branch ----
git push origin -d improve-documentation

## List all git branches (remote included) ----
git branch -a

## Download all remote branches ----
git fetch

## Create a new local branch from a remote branch ----
git checkout -b implement-feature origin/implement-feature
```