# Working with remotes
Remote repository is any repository that is hosted on the internet.

## Remote repository can be on local machine
Just, remote means else where

orgin - ` default server name that you have cloned`

`git remote`- orgin

`git remote -v` -list rhe severs

`git remote add [options]<name> <url>` - To add any remote url , name option to set the url name

`git fetch <remote> `- to get data from repository

Pulls the data from the remote that you don't have yet and you can able to merge your branches since you have references

`git remote rename x y `

'git remote remove x`

Why push?
Since I will work locally, to update my git repo in git server simple..

When to use gitpull
`git pull`

## Now talk about upstream

When a project at a time that you want to share,you have to push it to upstream

`git push orgin main`- saying to orgin server,please merge my local main branch in your `main` branch



