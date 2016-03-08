#如何在github上关联自己的项目

##first step
>* 在自己想要放置项目的地方建立一个文件夹，然后通过git init建立一个仓库,当然前提是需要下载git本身

##second step
>* 进入这个文件夹后，添加远程仓库，git remote add origin https://github.com/vigoss1944/bluenode.git
>* 然后就可以推送到master分支,先pull origin master

#如何建立分支，以及推送分支（初始化）
>* 可以先用git branch 来查看自己有多少个分支和处于哪个分支上
>* 第一次建立分支git checkout -b yourOwnFeature
>* 以后切换分支可以直接git checkout yourOwnFeature
>* 作为建立人需要把最开始的东西push上去,git push origin master(当然是前提要git checkout yourOwnFeature,切换到新建立的分支上)

#一套简单的git 协作流流程

## git status
> 查看本地是否有需要提交的东西

## git add 
> 添加修改的东西到本地

## git commit -m "leave note to this commit"
> 提交添加的修改到本地仓库

## git push origin master/dev/feature-bid (3个不同的分支，按自己的分支来提交)
> 推送到远程仓库

## git pull origin master/dev/feature-bid
> 从远程仓库更新最新文件 

## git remote add ditrepo git@112.74.92.121:ditrepo.git
> 新建的仓库, git pull/push ditrepo feature-bid

# 如何用screen命令

## screen -ls
> 查看screen中有多少个进程在跑

## screen -r 
> 进入到一个screen中

## ctrl+A+D
> 从一个screen中退出来并且detach掉

## screen -d
> 是把attach的进程detach掉

## screen -a
> 是把detach的进程attach掉

## 在screen中exit掉，就是结束这个screen进程

## screen -S
> 开启某个screen
