# litterbox

Test out git remote prune, git prune, git fetch --prune

there are 3 places we can see our branches:
1.remote
2.local-remote (ref/remote)
3.local

git fecth sync up remote and local-remote. 

git branch -a show you local and local-remote

local remote will not remove ref unless you use purge 

1. git remote prune origin

when you have a branch deleted on remote. sync up your local ref/remote with it. 

git branch -dr origin/[your branch name]

only delete ref/remote. no actual branch is delete from remote. 

git branch -d [your branch name]

does not delete ref/remote, obvious nor remote. 
