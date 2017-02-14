---
title:  "Git"
subtitle: "Common Git Command"
author: "Naib"
avatar: "img/authors/wferr.png"
image: "img/git.png"
date:   2017-02-14 12:12:12
---

### Configure the author name and email address
git config --global user.name "Sam Smith"
git config --global user.email sam@example.com

### Create a new local repository
git init

### Create a working copy of a local repository:	
git clone /path/to/repository


### For a remote server, use:	
git clone username@host:/path/to/repository

### Add one or more files to staging (index):	
git add <filename>
git add *

### Commit changes to head (but not yet to the remote repository):	
git commit -m "Commit message"

### Commit any files you've added with git add, and also commit any files you've changed since then:	
git commit -a

### Send changes to the master branch of your remote repository:	
git push origin master

### List the files you've changed and those you still need to add or commit:	
git status