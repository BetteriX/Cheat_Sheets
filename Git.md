## Installation:

### Linux:
On Linux, git can be installed easily with the available package manager.
With Debian based systems:
```bash
apt install git
```

### Windows:
On Windows, Git can be installed by downloading the installer from the [download page of Git](https://git-scm.com/downloads).
Or with winget:
```bash
winget install git
```

## Configuration:
First you need to assign the username and your email:
```bash
git config --global user.name "YourUsernameHere"
```

```bash
git config --global user.email "name@mydomain.com"
```

And now you can use git.

## Basic Commands:

|Git Command|Comment|
|---|---|
|`git init`|Initialize a directory as git managed repository|
|`git clone <url>`|Clone a remote repository to your local client|
|`git status`|Shows uncommited changes, new files etc.|
|`git add <file>`|Stage an updated / new file to the next commit|
|`git rm <file>`|Remove a file and stage the removal for the next commit|
|`git commit -m "message"`|Commit staged changes under a new commit|
|`git commit`|Will open an editor to write more descriptive commit messages. See [here](https://cbea.ms/git-commit/) for a guide on good commit messages|
|`git log`|Shows a list of commits in the current branch|
|`git log --pretty=oneline`|Shows a list of commits in the current branch in one line|
|`git log --patch`|Shows a list of commits in the current branch with the changes|
|`git reset <commit>`|Reset the current branch to the given commit|
|`git reset --hard <commit>`|Reset the current branch to the given commit and discard all changes|
|`git reset --soft <commit>`|Reset the current branch to the given commit and keep all changes staged|
|`git checkout <branch>`|Switch to another branch|
|`git branch`|Shows a list of existing branches|
|`git branch <branch>`|Creates a new branch (from the currently checked out branch)|
|`git merge <branch>`|Merge changes from `branch` to the currently checked out branch|
|`git push`|Push commited changes to the remote repository|
|`git pull`|Pull current state from the remote repository to your local repo|



