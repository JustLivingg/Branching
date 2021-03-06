## Git Cheatsheet

Summary of useful `git` commands.

### Basic Commands
* `git init` - Initialize local git repository
* `git status` - Show status of working directory
* `git add .` - Add everything in current directory to git index
* `git commit -m "Some message"` - Commit current work to local respository
* `git log` - Show git commit history
* `git log --oneline` = Show git commit history (compact)
* `git config -l` - List git configurations


### Branching Commands
* `git branch` - List branches in current repository
* `git branch someBranch` - Create branch `someBranch`
* `git checkout someBranch` - Move to new created branch `someBranch`
* `git checkout -b otherBranch` - Create and checkout `otherBranch`  

### Remote Commands
*  `git remote add origin URL` - Set remote repository alias `origin` for github URL
