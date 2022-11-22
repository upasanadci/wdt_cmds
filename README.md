# Git Hub Commands
## Configure the author name and email address to be used with zour commits.


- git config  - - global user.name "your user name"
- git config  - -global user.email "your email address"

## create a new local repository

 - git init
 
## checkout a repository
 - git clone /ssh path

## Add files

 - git add .
 - git add "file name"

## commit changes to head (not to remote repo)
  - git commit  -m "file has changed"
  
## commit any file that you have added with git add

  - git commit  -a
  
## send changes to the master branch of your remote repository

  - git push origin master
  
## if you have not connected your local repo to a remote server
  - git remote add origin "url"
  
## list all the remote repo 
  - git remote  -v
  
## create a new branch 
  - git checkout  -b branch name

## switch from one branch to another
   - git checkout branch name

## list all the branches in your repo also tell your current branch
  - git branch

## delete the branch
  - git branch  -d branch name

## push the branch to your remote repository
  - git push origin branch name
  
## push all the branches to remote repositorz
  - git push  - - all origin
  
## fetch and merge changes on the remote server
  - git pull

## to merge a branch
  - git merge branch name

## analysis the changes
  - git status

## history
   - git log

## SSh key setup
    -  ssh-keygen -t ed25519 -C "your email address"
    -  ls -al ~/.ssh
    -  cd .ssh
    - cat ~/.ssh/id_ed25519.pub

   
  

