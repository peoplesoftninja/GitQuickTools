# GitQuickTools

## To push a new repository/repo (folder) to a git repo

* on github.com create a new repo, copy the `.git` url
* cd to the folder
* git init
* git add *
* git status # make sure all files are added
* git commit -m `message`
* git remote add origin `.git` url
* git push -u origin master

## To push an existing repo

* cd to the folder
* git add *
* git status # make sure all files are added
* git commit -m `message`
* git push -u origin master

## To push a single file

* cd to the folder
* git add `filename`
* git status # make sure all files are added
* git commit -m `message`
* git push -u origin master

## setup git to point to a new github account

* cd to folder
* git init
* git config --global user.name `git user name`
* git config --global user.email `git account email`
* Go to Credential Manager
* Go to Windows Credentials
* Delete the entries under Generic Credentials

For more info on this

[Link - Windows](https://stackoverflow.com/questions/15381198/remove-credentials-from-git)

[Link - Mac](https://superuser.com/questions/1064197/how-to-switch-git-user-at-terminal)