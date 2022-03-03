# Frequenly used git command
## clone git remote repository
`git clone <git_repo>`
`git clone -b develop <git_repo>`   => clone project from remote with specific branch

## config
`git config --global user.email "satit.seetad@gmail.com"`<br>
`git config --global user.name "satit.seetad"` <br>
`git config --global --list`<br>

## create git local repository
`git init`

## add file to the track
`git add <file>`            => use . for all files

## commit file with comment
`git commit -m "<comment>"`

## manage branch
`git branch`		        => see local branches<br>
`git branch -r`	            => see remote branch<br>
`git branch -a`	            => see local/remote branch<br>
`git branch <branch>`	    => create new branch<br>
`git branch -d <branch>`	=> delete branch<br>
`git branch -M <branch>`    => rename branch<br>

## add remote repository
`git remote add origin https://github.com/satit-seetad/es.git`

## push to remote repository
`git push`                      <br>
`git push -u origin [branch]`   <br>
`git push -u origin HEAD`       <br>

## check status
`git status`		=> check status

## show head
`git show HEAD`

## checkout
`git checkout HEAD <file>`
`git checkout <branch>`	    => switch branch<br>
`git checkout -b <branch>`	=> create branch and switch<br>
`git checkout -b <branch> <based branch>`	=> create branch from based branch<br>
`git checkout --track origin/<branch>`	=> swith remote branch

## log
`git log`

## show all remote branches
`git ls-remote`	=> list remote

## show all remote repository
`git remote -v`

## fetch code from remote repository
`git fetch`	=> fetch remote to local

## merge
`git merge <branch_name>` => merge code to local<br>
`git merge origin/master` => merge remote to local<br>

## pull
`git pull`				=> git fetch + git merge<br>
`git pull origin [branch] --allow-unrelated-histories`	=> fix problem git pull refusing to merge unrelated histories

## reset
`git reset --hard HEAD`   => reset the local changes to original version
