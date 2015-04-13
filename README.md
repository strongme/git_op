#Git init
``` shell
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/strongme/git_op.git
git push -u origin master
```

#Git branch
``` shell
#列出所有分支
git branch
#创建分支
git branch (branchname)
#切换到branchname分支
git checkout branchname
#创建并切换到branchname分支
git checkout -b branchname
#修改本地文件，并创建远程develop分支
git remote add develop https://github.com/strongme/git_op.git
git push develop master
```