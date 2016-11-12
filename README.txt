git learn:

git init 			初始化仓库
git add <file> 			添加文件
git commit -m "" 		提交文件，并添加说明
git status  			查看文件修改情况
git diff                	查看文件不同
git log --pretty=oneline 	查看历史提交日志
get reset --hard 		回退版本 PS: HEAD表示当前版本，HEAD^上一个版本，HEAD~100前100个版本，指定commit id
git reflog			查看命令历史
git checkout --file		捡出版本库或者暂存区文件
git reset HEAD file		撤销暂存区的修改
git rm 				删除版本库中的文件
git push -u origin master	将本地库内容推送到远程
