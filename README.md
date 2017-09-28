# drag
拖拽的项目


安装完成后，还需要最后一步设置，在命令行输入：

$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

git下面的所有配置

$ git config --list 

查看状态

$ git status

添加 文件到暂存区

$ git add 加文件名

把一个已有的本地仓库与github关联

$ git remote add origin http://XX

将本地的master分支推送到origin主机，同时指定origin为默认主机，后面就可以不加任何参数使用git push了

$ git push -u origin master