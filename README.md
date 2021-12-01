# thlabs-git
all about git flows, day to day scenarios for project 
- git branch login_support origin/support 
- Update on the fly

If you want to create new branch at local from remote branch  (repo branch)
 
- git checkout -b "bug/user-profile_new" origin/main

create branch from current working branch in your workspace

-  git checkout -b "bug/user-profile_new"


-- Stash command 


$ git stash apply stash@{0}

 - git stash save "no updating more config"
 
if files are added newly and you want to add inside stage -
  - you should be staging changes before saveing stash.. else newly added files not going to be part of saved stash
  
  
