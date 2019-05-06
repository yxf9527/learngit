1，在版本仓库（repository,一般目录）下右键git bash自动定位到版本库，但是目前状态还不归git管理，通过git init才能初始化该目录，使之成为版本仓库；命令执行后有个隐藏的.lsh文件生成

2，在该目录下新增一个文件readme1.txt和readme2.txt，文件内容随便；
git add readme1.txt readme2.txt         类似提交到缓存区  多个文件空格隔开
git commit -m "说明"                           正式提交
git status                                              查看当前文件状态 哪些文件改变了
git diff                                                  diff意为different   即show different 

注意点：
	git commit 只提交缓存区的文件 即文件必须通过git add命令增加到待提交区
	git diff 表示的是当前文件内容和上次已经提交的内容之间的比较，而不是和git add命令后的比较
             
