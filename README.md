# Git Cheetsheet
## General commands
#### Global config
```
$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"
```
#### Init git project
```
$ git init
```
#### Add a remote
```
$ git remote add <remote> <target-url>
```
#### Check remotes
```
$ git remote #Lists all remote
$ git remote -v #Lists all remote with path
```
#### Check the status
```
$ git status
```
#### Create a new branch
```
$ git branch <branch>
```
#### Check the branches
```
$ git branch
```
#### Switch to branch
```
$ git checkout <branch>
```
#### Merge a branch to current scope
```
$ git merge <remote>/<branch>
```
#### Clone directory
```
$ git clone <url>
```
#### Add files to track
```
$ git add .
```
#### Commit changes
```
$ git commit -m "Message"
```
#### Push the commit
```
$ git push -u <remote> <branch>
```
#### Fetch the data into local dir
```
$ git fetch <remote> <branch>
```
#### Pull (Fetch and merge) into local dir
```
$ git pull <remote> <branch>
```

## Use cases
### Get lastest changes from master into dev branch
1. **Get the latest changes of master**

	*Be sure to be on the right branch*

	```
	$ git checkout <branch>
	```  
	
	*Pull the changes into local dir*
	
	```
	$ git pull <remote> <branch>
	```
	
2. **Push the changes into the branch**
	
	```
	$ git push
	```

----

### Commit, push and merge latest changes from dev branch into master
1. **Add files to track**  

	```
	$ git add .
	```

2. **Commit changes**  

	```
	$ git commit -m "Message"
	```

3. **Push into the branch**

	```
	$ git push -u <remote> <branch>
	```
	
----

More [here](ttps://www.atlassian.com/git/tutorials/)
