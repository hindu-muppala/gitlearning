| Command | Description | Example |
| --- | --- | --- |
| `git status` | List all *new or modified* files | git status |
| `git diff` | Show file differences that **haven't been** staged | git diff |
| `git commmit -a` | by -a tag ,commit tracked files (no need for git add ) | git commit -a -m "git is super" |
| `git rm` | rm file or directory from tracked | git rm projet |
| `git rm --cached` | only removes from track | git rm --cached file|
|git log --pretty=format:"%h %s" --graph|
|git log -- path/to/fil| 
| git commit --amend | 
| `git restore --staged contribe.md`| stage to unstage||
|`git restore`| set the files to last commit||
|`git reset HEAD CONTRIBUTING.md` |
| git checkout -- CONTRIBUTING.md |
 | git restore --staged| staged to unstaged | git reset --staged contibute.md|
 | git mv file1 file2 | change the file name from file1 to file2 |
 | git restore | replaces with `last staged` or `commited`|
 | `git branch -d branchName` | Deleteing the branch ||'
 | `git branch branchName` | creating new branch branch name||
 | `git checkout branchName ` | switch to branchname ||
 | `git checkout -b branchName ` | creating+checkout ||
 |`git branch` | list all branches| |
 | `git merge branchname`| mearge current branch to branchname |
 | 'git fetch` | fetch data from remote repository | git fetch origin |
 | `git --move br1 br2` | rename branch1 to branch2 |
 | `git push remoteUrl branch` | pushing local branch to remote repository|
 
