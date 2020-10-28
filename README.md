## Git Cheat Sheet


Summary of useful `git` commands.

### Basic Commands
* `git init` Intitialize local git repository
* `git status` - show status of working directory
* `git add .` - add everything in current directory to git index

* 'git commit -m "Some Message"' - commit current work to local repository
* 'git log' - show git commit history
* 'git log --oneline' - show git commit history (compact)
* 'git config -l' - List git configuration

* `git commit -m "Some Message"` - commit current work to local repository
* `git log` - show git commit history
* `git log --oneline` - show git commit history (compact)
* `git config -l` - List git configuration



### Branching Commands
* `git branch` - List branches in current repository
* `git branch someBranch` - Create branch 'someBranch'
* `git checkout someBranch` - Move to branch 'someBranch'
* `git checkout -b otherBranch` - Create and checkout 'otherBranch'
* `git pull origin main` - Pull remote `main` into current branches
* `git push origin newBranch` - Push current committed branch to remote 

### Remote Commands
* `git remote add origin URL` - Set remote repository alias '.origin' for github 'URL'
