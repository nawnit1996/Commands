Git Commands
============


### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | To get comprehensive status. |
| `git status --short` | To get simplified git status. |
| `git diff` |  The result tells you the changes you’ve made that you haven’t yet staged. |
| `git diff --staged` |  If you want to see what you’ve staged that will go into your next commit. |
| `git add [filename]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name]` | Remove a file (or folder) |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push [Remote] --delete [branchName]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] [Remote]/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git fetch [remote]` | Update remote tracking branch to latest commit. |
| `git merge [remote]/[branch]` | Merge change in remote/branch to current HEAD |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push [remote] [branch name]` | Push a branch to your remote repository |
| `git push [remote] --delete [branch name]` | Delete a remote branch |
| `git pull [Remote] [branch]` | fetches changes from remote repo and merges branch mentioned to local HEAD|
| `git remote add [Remote] ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url [Remote] ssh://git@github.com/[username]/[repository-name].git` | Set a repository's [Remote] branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git diff [source branch] [target branch}` | Preview changes before merging |

