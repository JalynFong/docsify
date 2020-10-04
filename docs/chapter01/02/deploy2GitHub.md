<!-- docs/chapter01/02/local-view.md -->

# 部署到GitHub Pages

GitHub Pages 支持从三个地方读取文件:
- 1、 master分支
- 2、 master分支下的 docs目录
- 3、 gh-pages分支

&nbsp; &nbsp; &nbsp; &nbsp; 如果你的文档直接是在项目根目录写的，那么可直接把代码推送到master分支上， GitHub Pages里选择 master branch.

&nbsp; &nbsp; &nbsp; &nbsp; 如果你的文档是在master分支下的 docs/目录下编写的，那么可直接把代码推送到master分支上， GitHub Pages里选择 master branch/docs folder.

本例子项目是直接在根目录中编写的，所以GitHub Pages里选择master branch的方式部署。

首先在github网站上创建好仓库，然后终端打开项目目录：
```bash

git init
git add .
git commit -m 'docsify项目初始化'
git remote add origin https://github.com/username/docsify.git
git push --set-upstream origin master
```

代码推送到github上后，打开github的仓库，选择Settings -> GitHub Pages -> master branch -> save。