常用Git命令：
1、git init                            把当前目录变成Git可以管理的仓库
2、git add readme.txt                  告诉Git，把文件readme.txt添加到仓库
3、git commit                          告诉Git，把文件提交到仓库
4、git commit -m "wrote a note file"   同3，-m后面输入的是本次提交的说明
5、git status                          可以让我们时刻掌握仓库当前的状态，查看是否有改动
6、git diff                            顾名思义就是查看difference
7、git log                             显示从最近到最远的提交日志
8、git reset --hard commit_id          回退版本
9、git reflog                          用来查看你的所有命令
10、git checkout -- <file>             丢弃工作区的修改
11、git reset HEAD file                可以把暂存区的修改撤销掉（unstage），重新放回工作区;git reset命令既可以回退版本，也可以把暂存区的修改回退到工作区。当我们用HEAD时，表示最新的版本。

场景1：当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令git checkout -- file。

场景2：当你不但改乱了工作区某个文件的内容，还添加到了暂存区时，想丢弃修改，分两步，第一步用命令git reset HEAD file，就回到了场景1，第二步按场景1操作。

12、git rm                             用于删除一个文件。如果一个文件已经被提交到版本库，那么你永远不用担心误删，但是要小心，你只能恢复文件到最新版本，你会丢失最近一次提交后你修改的内容。
13、git remote add origin git@server-name:path/repo-name.git  关联一个远程库
14、git push -u origin master          第一次推送master分支的所有内容，此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改
15、git clone                          克隆远程仓库
16、git branch                         列出所有分支，当前分支前面会标一个*号
17、git merge                          用于合并指定分支到当前分支
18、git branch -d <name>               删除分支
19、git checkout -b dev                表示创建并切换，相当于两条命令 ---> git branch dev + git checkout dev
20、git branch <name>                  创建分支
21、git checkout <name>                切换分支
22、
23、
24、
25、
26、
27、
28、
29、
30、




