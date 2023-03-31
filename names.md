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

## What happens when commit?
Let consider three files to stagged and committed . Since we know that git records snap shots not difference. It will create meta data and objects.

Objects such that :- let understand by example , in our case a root object is created which has reference to three files information, and three objects of the file and meta data which has information.
![image](https://user-images.githubusercontent.com/120579608/225814224-52cf73de-e42a-4321-b770-f9cd67ad7f33.png)

![image](https://user-images.githubusercontent.com/120579608/225814525-1883795b-4a05-4efa-bfc9-cf76a74208fc.png)

## Let talk about branching
The default is master, but it is like other branches only.When we create new branch , it will refers to the present commit.

![image](https://user-images.githubusercontent.com/120579608/225816610-ce26e1db-9b9a-43f0-9901-a3c44c4dca29.png)
 `git log --oneline --decorate` --> once run to know the branch references
 
 `git branch testing` --> creates new branch testing
 
 `git checkout testing` --> moves `head` pointer to the branch
 
 ![image](https://user-images.githubusercontent.com/120579608/225817252-52f3c24e-8e16-4815-a22f-5ac3e5afcb54.png)
 
 ![image](https://user-images.githubusercontent.com/120579608/225817369-d3b23dc1-48f9-4996-a1f5-bbe2214b1ecf.png)

git log --oneline --decorate --graph --all
## Now about "merging"
### forward merging (direct ancestor)
![image](https://user-images.githubusercontent.com/120579608/229003367-84e87e63-2d4f-4531-8980-a8dd64e8c990.png)
![image](https://user-images.githubusercontent.com/120579608/229003468-4e658fea-eb92-41fb-9df1-ccd9e0c26673.png)


### recursive merging (common ansector)
![image](https://user-images.githubusercontent.com/120579608/229003140-a67baf5c-b71c-4d9b-a6a8-47f551db9b0d.png)
![image](https://user-images.githubusercontent.com/120579608/229003549-100f0413-3917-435e-996e-4edb324b9d28.png)

