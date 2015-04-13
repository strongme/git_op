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

#Git merge
#合并分支
#查看当前分支
git branch  
* master
  develop
git merge develop
Updating c5750a1..86c55cd
Fast-forward
 README.md | 17 ++++++++++++++++-
 1 file changed, 16 insertions(+), 1 deletion(-)
 #提交合并后的master分支到远程
 git push origin master
 Username for 'https://github.com': strongme
Password for 'https://strongme@github.com':
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/strongme/git_op.git
   c5750a1..86c55cd  master -> master
```