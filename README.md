README
============================
该文件是介绍git相关使用的。主要是命令行的使用。推荐可视化客户端SourceTree,不过稳定性有待提高。

****
###                 Author:liuyong
###             E-mail:liuyonghui123@aliyun.com

===========================


##<a name="index"/>目录
1.git的基本知识
----------------------------


[廖雪峰git教程网址](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001373962845513aefd77a99f4145f0a2c7a7ca057e7570000 "git 教程")

* [分支](#line)
>>查看分支：git branch

>>创建分支：git branch <name>

>>切换分支：git checkout <name>

>>创建+切换分支：git checkout -b <name> 创建新分支并切换到新建分支

>>合并某分支到当前分支：git merge <name>

>>删除分支：git branch -d <name>

>>强制删除分支：git branch -D <name>

>>创建与远程分支关联的分支： git checkout -b <branchname> <origin/branchname>

>代码修改

>>推送自己的修改： git push origin <branchname>

>>拉取服务器代码： git pull

>>查看远程库的信息： git remote -v

>>推送本地分支： git push origin <branchname>

>>建立本地分支与远程分支的关联： git branch --set-upstream
        
        git status 查看当前分支状态<br>
        git branch 查看当前所在分支<br>
        git init 初始化版本库<br>
        git branch -a 查看服务器分支<br>
        git stash 将当前分支暂存<br>
        git stash apply 将暂存内容恢复，单暂存的内容不删除<br>
        git stash drop 删除暂存的内容，用在恢复之后 <br>
        git stash pop  恢复暂存的同时删除stash内容 <br>
        git reset --hard <branchnum> 回退到某个提交
        git log  打印提交记录
        git reflog  查看命令历史
        

**************************************************************
