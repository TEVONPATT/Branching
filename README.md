## Git Cheatsheet
Summary of useful `git` commands.
### Basic Commands
* `git init` - Initialize local git repository
* `git status` - Show status of working directory
* `got add .` - Add everything in current directory to git index
* `git commit -m "Some message"` - Commit current work to local repository
* `git log` - Show git commit history
* `git log --oneline` - Show git commit history (compact)

### Branching Commands
* `git branch` - List branches in current repository
* `git branch someBranch` - Create branch `someBranch`
* `git checkout someBranch` - Move to branch `someBranch`
* `git config -l` - List git configuration
* `git pull origin main` - Pull remote `main` into current branches
* `git push origin newBranch` - Push current branch to remote
