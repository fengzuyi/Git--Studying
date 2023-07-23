# Git--Studying

**Git学习记录**  

---

> git客户端下载官网地址：https://git-scm.com/download/win/ （选择自己需要的版本下载，无脑式安装就好，可以改一下安装路径（默认C盘））  
> 安装完成之后得配置用户名和邮箱，点这[SSH](https://github.com/fengzuyi/Git-SSH.git) 😘
---
**一、命令集**  
| Git常用命令    | 作用    |
| ------------  | :------ |  
| git config --global user.name 用户名   |    设置用户签名 |  
| git config --global user.email 邮箱  |       设置用户签名|  
| git init      |                              初始化本地库|  
| git status     |                             查看本地库状态|  
| git add 文件名     |                          添加到暂存区|  
| git commit -m "日志信息" 文件名    |             提交到本地库|  
| git reflog                    |               查看历史记录|  
| git reset --hard 版本号          |             版本穿梭|  
> [vim基本使用](https://github.com/fengzuyi/vim)  

**二、分支**  
1. 什么是分支？
  > 在版本控制过程中，同时推进多个任务，为每个任务，我们就可以创建每个任务的单独分支。
2. 分支的操作
> 
| 命令名称    | 作用  |  
| ------------  | :------ |  
| git branch 分支名 | 创建分支 |  
| git branch -v | 查看分支 |  
| git checkout 分支名 | 切换分支 |  
| git merge 分支名 | 把指定的分支合并到当前分支上|  
3. 合并分支（冲突合并）  
  > 如果两个分支都修改并且合并，会产生冲突，需要手动解决冲突。
4. 远程库
> 
| 命令名称 | 作用 |
| ------- | :-------- |
| git remote -v | 查看当前所有远程地址别名 |
| git remote add 别名 远程地址 | 起别名 |
| git push 别名 分支 | 推送本地分支上的内容到远程仓库 |
| git clone 远程地址 | 将远程仓库的内容克隆到本地 |
| git pull 远程库地址别名 远程分支别名 | 将远程仓库对于分支最新内容拉取下来后与当前本地分支直接合并 |

---
> 注意：在拉取和推送是用https的方式容易出错，建议用[SSH](https://github.com/fengzuyi/Git-SSH.git)拉取私人库比较方便。


