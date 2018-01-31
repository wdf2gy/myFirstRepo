# 我的第一个Git仓库

### **Quick setup** — if you’ve done this kind of thing before

SSH  git@github.com:wdf2gy/myfirstrepo.git

We recommend every repository include a [README](https://github.com/wdf2gy/myfirstrepo/new/master?readme=1), [LICENSE](https://github.com/wdf2gy/myfirstrepo/new/master?filename=LICENSE.md), and [.gitignore](https://github.com/wdf2gy/myfirstrepo/new/master?filename=.gitignore).

### …or create a new repository on the command line

```
echo "# myfirstrepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:wdf2gy/myfirstrepo.git
git push -u origin master

```

### …or push an existing repository from the command line

```
git remote add origin git@github.com:wdf2gy/myfirstrepo.git
git push -u origin master
```