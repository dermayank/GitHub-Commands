# GitHub-Commands

`git init`  initalizes an empty git hub repository

`git clone [SSH url]`  clones the github repository to local working directory

`git add .`

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

`git stash drop stash@{2}`	deletes only the stash no. 2

