# litterbox

Test out git remote prune, git prune, git fetch --prune
there are 3 places we can see our branches:

remote
local-remote (ref/remote)
local

git fecth sync up remote and local-remote. 

git branch -a show you local and local-remote

local remote will not remove ref unless you use purge 

1. git remote prune origin
when you have a branch deleted on remote. sync up your local ref/remote with it. 
