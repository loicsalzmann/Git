# Git Cheetsheet
## General commands
#### Global config
```javascript
$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"
```
#### Init git project
```php
$ git init
```
#### Add a remote
```php
$ git remote add [remote] [target-url]
```
#### Check remotes
```php
$ git remote -v
```
#### Check the status
```php
$ git status
```
#### Create a new branch
```php
$ git branch [branch]
```
#### Check the branches
```php
$ git branch
```
#### Switch to branch
```php
$ git checkout [branch]
```
#### Merge a branch
```php
$ git merge [branch]
```
#### Clone directory
```php
$ git clone [url]
```
#### Add files to track
```php
$ git add .
```
#### Commit changes
```php
$ git commit -m « Message »
```
#### Push the commit
```php
$ git push -u [remote-name] [branch]
```
#### Fetch the data into local dir
```php
$ git fetch [remote]
```
#### Pull (Fetch and merge) into local dir
```php
$ git pull [remote] [branch]
```

## Use cases
### Get lastest changes from master into dev branch
1. **Get the latest changes of master**  
*Be sure to be on the right branch*  
```
$ git checkout [branch]
```  
*Pull the changes into local dir*  
```
$ git pull [remote] [branch-to-get]
```

3. **Push the changes into the branch**  
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
$ git push -u [remote-name] [branch]
```

----
