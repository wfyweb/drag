# git 总结

安装完成后，还需要最后一步设置，在命令行输入：

$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

git下面的所有配置

$ git config --list 

查看状态

$ git status

添加 文件到暂存区

$ git add 加文件名

添加远程版本库

$ git commit -m “你的备注信息”

直接从工作区 到 暂存区 到 版本区

$ git commit -a -m “注释”

把一个已有的本地仓库与github关联

$ git remote add origin http://XX

将本地的master分支推送到origin主机，同时指定origin为默认主机，后面就可以不加任何参数使用git push了

$ git push origin

上面命令表示，将当前分支推送到origin主机的对应分支。

如果当前分支只有一个追踪分支，那么主机名都可以省略。

$ git push -u origin master

上面命令将本地的master分支推送到origin主机，同时指定origin为默认主机，后面就可以不加任何参数使用git push了。

不带任何参数的git push，默认只推送当前分支，这叫做simple方式。此外，还有一种matching方式，会推送所有有对应的远程分支的本地分支。Git 2.0版本之前，默认采用matching方法，现在改为默认采用simple方式。

