有关于本地仓库
git add -A 提交所有变化
git add -u 提交被修改和被删除的文档，不包括新文件
git add . 提交新文档和被修改文件，不包括被删除文件
git status 查看文件状态

git commit -m "输入注释 "

远程仓库
SSH中含有连接远程仓库的命令
git remote -v 验证添加成功的远程仓库
远程仓库的代称是origin
断开连接命令 git remote remove origin
git push origin master 将远程仓库同步
git pull origin 更新本地地址


克隆远程仓库
git clone +地址

分支
git branch name 创建分支
git checkout name  切换分支
git branch 查看所有分支