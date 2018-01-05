# Git学习笔记，常用命令

## 本地环境下常用的基本命令
- git status ： 查看当前git仓库的状态
- git init ： 初始化git仓库，创建一个git仓库，生成了.git文件夹
- git add xx.xx ： 把改动添加到一个「暂存区」，可以理解成是一个缓存区域，临时保存改动
- git commit -m "commit message" ： 提交缓冲区的改动；-m代表提交信息，windows系统使用双引号""将信息括起来
- git log ： 查看git commit的记录
- git branch ： 查看当前分支情况；git init初始化后会默认生成一个主分支master，即默认分支
- git branch a ： 新建一个名为a的分支
- git checkout a ： 切换到a分支
- git checkout -b a ：新建一个名为a的分支，并自动切换到a分支
- git merge : 合并分支；（如果你在a分支下完工了，需要把自己的代码合并到master主分支上，需要做两步，一：切换到master分支上，二：git merge a;如果没有               冲突这就会使a分支的代码成功合并到master上来）
- git branch -d a ：删除a分支
- git branch -D a : 强制删除a分支；（如果a分支的代码还没有合并到master分支上，可能会删除失败，这时候可以使用-D强制删除）
- git tag ： 查看历史tag（版本）记录
- git tag v1.0 ： 在当前代码状态下新建了一个v1.0标签
- git checkout v1.0 ： 切换到v1.0版本代码状态

## 涉及到与远程仓库协作的命令
