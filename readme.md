# gitTest
### …or create a new repository on the command line
``` 
echo "# gitTest" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ghairui/gitTest.git
git push -u origin master
```
### …or push an existing repository from the command line

```
git remote add origin https://github.com/ghairui/gitTest.git
git push -u origin master
```
上面git remote add时报已存在，当修改的时候，再次提交

```
git add .
git commit -m "second commit"
git push -u origin master
先将当前目录下暂存、提交，然后推送到远程master主干

```

