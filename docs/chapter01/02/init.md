<!-- docs/chapter01/02/init.md -->

# 1.2 快速开始

## 初始化项目

如果想在项目的 ./docs 目录里写文档，直接通过 init 初始化项目。

```bash
docsify init ./docs
```

## 开始写文档

初始化成功后，可以看到 **./docs** 目录下创建的几个文件
* **index.html** 入口文件
* **README.md** 会做为主页内容渲染
* **.nojekyll** 用于阻止 GitHub Pages 忽略掉下划线开头的文件

直接编辑 docs/README.md 就能更新文档内容，当然也可以添加更多页面。


## 本地预览

通过运行 **docsify serve** 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 http://localhost:3000 。
```bash
docsify serve docs
```
更多命令行工具用法，参考 [docsify-cli 文档](https://github.com/docsifyjs/docsify-cli)。