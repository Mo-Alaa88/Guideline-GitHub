# Guideline GitHub 

## Create Repo
* Initialization repo `git init`
* Add X file `git add X`
* Add all files `git add .`or `git add *`
* Add your commit `git commit -m 'Your commit'`
* Add a remote`git remote add origin `+`your link repo`
* Upload local repo on cloud master repo `git push origin master`

## Update Cloud Repo
* Add all files `git add .`or `git add *`
* Add your commit `git commit -m 'Your commit'`
* Update cloud master repo `git push origin master`

## Update Local Repo
* Write this command line`git pull origin master`

## How can I add team members to push & pull in your Project
* Go to `Settings` in your repo
* Then `Collaborators` 
* Search by username, full name or e-mail address 
* Click `Add Collaborators`

## How to remove folder from github
* NOTES!! If you want to remove some folders or files from Git or github don't remove by just pressing the delete button but follow this steps
* Remove folder from your repo by `git rm -r --cached `+`your file name`
* Then add your commit `git commit -m 'Remove your folder name'`
* Update cloud master repo `git push origin master`
* Now you can delete your folder or file from your device by pressing the delete button

## Some Tips
* To show the content of your directory type the list command `ls`
* You can know your git status by typing `git status`
* You can add documentation to your project by using Wiki button on github site or through using README.md file. **I recommend using README** because github display the README file in the first page. **YOU ARE NOW READING THIS ARTICLE FROM README.MD** [Basic writing .md](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji) :+1:

## Create new branch & manage other branches 
* If you want to create a new branch write this command line `git checkout -b `+`name of your new branch`
* To display all commit type `git log`
* Then paste your branch link after `git Checkout `+`branch name`
* If you need to display all your local branches use `git branch`
	* you currently at master branch , look at this example
	```terminal
	* master
	your branch
	```
* If you need to display all your branches on github use this command `git branch -a`
	you will get output like this
	```
	remotes/origin/HEAD -> origin/master
  	remotes/origin/master
  	remotes/origin/request
	```
* If you need to pull any branch from github use this command`git branch -b 'request' 'origin/request'`
* To upload your local branch repo to your cloud branch use this command `git push origin `+`branch name`



