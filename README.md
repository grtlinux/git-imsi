# git with command
```
$ mkdir git-test && cd $_
$ mkdir git-test01 && cd "$_"
$ git init
$ echo "## git-test01" >> README.md
$ git add *
$ git status
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin https://github.com/grtlinux/git-tips.git
$ git push origin master
```
```
$ git init
$ git remote add origin https://github.com/grtlinux/git-tips.git
$ git pull origin master
```

```
[ make any repo in github.com ]

$ mkdir cookbook && cd $_

$ git init
$ git branch -M main
$ git remote add origin https://github.com/grtlinux/KieaPython22.git
$ git pull origin main
    ...

[ update or create articles ]
$ tree *

$ git add --all
$ git add -A
$ git status
$ git commit -m "update sources"
$ git branch
$ git push origin main

[ check the repo in github.com ]

$ cd ..
$ rm -rf cookbook

```

# Find files in Github
- Select any repository
- Press [t]
