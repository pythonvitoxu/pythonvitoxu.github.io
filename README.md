# pythonvitoxu.github.io

#文章生成
```
pelican content
```

#本地允许博客
```
cd ~/project/yoursite/output
python -m pelican.server
```

#创建本地版本库
```
git init
```

#把文件添加到版本库
```
git add .
git commit -m "注释"
```

#关联远程仓库
```
git remote add origin git@github.com:michaelliao/learngit.git
git push origin master （git push -u origin master 初次要加上 -u参数）
```
