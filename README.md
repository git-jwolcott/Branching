## Git Cheat sheet

Summary of useful `git` commands.

### Basic Commands
* `git init` - Initialize local git respository
* `git status` - Show status of working directory
* `git add .` - Add all changes to current directory to git index
* `git commit -m "commit message here"` - Commit current work to local repo
* `git log` - Show git commit history
* `git log --oneline` - Show git commit history (compact)
* `git config -l` - List git configuration

### Branching Commands
* `git branch` - List branches in current respository
* `git branch someBranch` - Create branch `someBranch`
* `git checkout someBranch` - Move to branch `someBranch`
* `git checkout -b otherBranch` - Create and checkout `otherBranch`

### Remote Commands
* `git remote add origin URL` - Set remote respository alias `origin` for `URL`
