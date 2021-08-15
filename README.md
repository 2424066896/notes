# notes
1. git init //初始化仓库

git add .(文件name) //添加文件到本地仓库

git commit -m “first commit” //添加文件描述信息

git remote add origin + 远程仓库地址 //链接远程仓库，创建主分支

git pull origin master // 把本地仓库的变化连接到远程仓库主分支

git push -u origin master //把本地仓库的文件推送到远程仓库

$git pull origin master --allow-unrelated-histories

git pull 命令基本上就是 git fetch 和 git merge 命令的组合体，Git 从指定的远程仓库中抓取内容，然后马上尝试将其合并进你所在的分支中。


