---
date: "2025-04-01"
title: Useful git Commands
---
**git config credential.helper store**

This saves your username and password for the project folder

**git config --local user.email "youremail@gmail.com"**

This saves your email to the local project

**git config --local user.name "arron"**

This saves your name to the local project

**git  fetch -p**

this looks at all local branches on your computer, then compares it to the remote repository. if the branch no longer exists on the remote repository then you "prune" it. this is good for cleaning up "stale" branches

**git remote -v**

this shows your git urls that you are fetching and push to

**git remote set-url origin https://myawesomerepository.git**

this changes the git url that your fetch and push to

**git remote show origin**

shows the URL of the git origin where you pull/push files to

**git remote rm testing**

removes the remote branch "testing"

**git revert 989189be8662ef4ba2bce3f6178f1a9c644fe0e7**

This will create a new commit that undoes the changes introduced by the specified commit.

**git  rebase**

