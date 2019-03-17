# GitHub-Commands

### Basic 

`git config --global user.name "user-name"` set local username

`git config --global user.email "user-email"` sets local useremail

`git init`  initalizes an empty git hub repository

`git clone [url]`  clones the github repository to local working directory

`git add .` add all the files in current directory only

`git add -A` add all the files to staging area

`git commit -m "the commit remark"`

`git push origin master` 

### Remote 

`git remote -v`  the url of remote directory

`git remote remove [origin]`

`git remote add [origin] [url]`

### Branch

`git branch` lists all the local branches, branch with * is the current branch

`git branch -a` lists all the local and remote branches

`git branch [branch-name]` creates a new local branch

`git branch -d [branch-name]` delete the local branch

`git checkout [branch-name]` switch to the branch

`git status`

### Stashing

`git stash` saves the local changes to the stack

`git stash list` list of stashes made

`git stash apply` it applies topmost stash to the repository

`git stash apply stash@{2}` it applies the stash no. 2 to the repository

`git stash pop` applies the stash and then delete it form the stack

`git stash pop stash@{2}` it applies the stash no. 2 to the repository and the delete it

`git stash clear` deletes all the stashes made in a repository

### Undo Commit

`git log` lists all the changes each with unique hash value

`git checkout [commit-hash]` make the working directory point to commit with given hash

`git checkout [branch-name]` makes the branch point to current hash