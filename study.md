 ### 创建版本库



git init 

git add .   / git add read.md

git commit -m "value"

### 版本跳转 

git reset --hard HEAD^ 回到上个版本

git log 查看所有的提交版本(当前提交版本之前的 

git log --pretty=oneline 一行展示

git log --graph 图表展示

git reflog   查看所有的提交 (所有的

git diff 

### 撤销修改

没有加到暂存区 stage 

git checkout -- file 修改的文件

已经加到 stage

git reset HEAD file 撤回到 工作区 

### 删除文件

git rm file

删除之后 需要 git commit 



### 远端 

git remote add origin master 

git push -u origin master 

 + clone 

   git clone

### 分支

 	创建分支 

​	git branch " name "

git checkout dev 

git switch dev 

git switch -c dev

git merge dev 

git merge --no-ff -m "merge" dev 合并

 + bug 修改

   git stash

