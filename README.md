# Guideline GitHub 

## Create Ripo
* Initialization repo `git init`
* Add X file `git add X`
* Add all files `git add .`or `git add *`
* Add your commit `git commit -m 'Your commit'`
* Add a remote`git remote add origin `+`your link ripo`
* Upload local repo on cloud master repo `git push origin master`

## Update Cloud Repo
* Add all files `git add .`or `git add *`
* Add your commit `git commit -m 'Your commit'`
* Update cloud master repo `git push origin master`

## Update local repo
* Write this command line`git pull origin master`

## How can I add team members to push & pull in your Project
* Go to `Settings` in your repo
* Then `Collaborators` 
* Search by username, full name or email address 
* click `Add Collaborators`

## How to remove folder from github
* NOTES!! If you want remove some folder or file from Git or github don't remove by just press delete button but follow this steps
* Remove folder from your repo by `git rm -r --cached `+`your file name`
* Then add your commit `git commit -m 'Remove your folder name'`
* Update cloud master repo `git push origin master`
* Now you can delete your folder or file from your device by press delete button

##
* You can know name children your direction by `ls`
* You can know your git status by `git status`
* You can add documentation by github site Wiki button or by README.md file **we recommend README** because github display that in first page **NOW YOU  READING THIS ARTICLE FROM README.MD** [Basic writing .md](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji) :+1:

## Create new branch & manage other branches 
* If you want to create a new branch write this command line `git checkout -b `+`name your new branch`
* We need display all commit by `git log`
* Then paste your branch link after `git Checkout `+`Your branch`
* If you need display all your local branches `git branch`
	* you tackling master branch look at this Ex
	```terminal
	* master
	your branch
	```
* If you need display all your branches on github `git branch -a`
	you will get response like
	```
	remotes/origin/HEAD -> origin/master
  	remotes/origin/master
  	remotes/origin/request
	```
* If you need pull any another branch on github`git branch -b 'request' 'origin/request'`
* Upload your local branch repo in your cloud branch `git push origin `+`your repo`



