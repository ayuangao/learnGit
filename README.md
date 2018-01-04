# Git学习笔记，常用命令
- git status ： 查看当前git仓库的状态
- git init ： 初始化git仓库，创建一个git仓库，生成了.git文件夹
- git add xx.xx ： 把改动添加到一个「暂存区」，可以理解成是一个缓存区域，临时保存改动
- git commit -m "commit message" ： 提交缓冲区的改动；-m代表提交信息，windows系统使用双引号""将信息括起来
- git log ： 查看git commit的记录
- git branch ： 查看当前分支情况；git init初始化后会默认生成一个主分支master，即默认分支
- git branch a ： 新建一个名为a的分支
- git checkout a ： 切换到a分支
- git checkout -b a ：新建一个名为a的分支，并自动切换到a分支
