---
title: github个人主页和项目主页
---
本文介绍下github个人主页以及项目主页的搭建方法。

##1.github个人主页
优点：
a、简单（不需自行搭建服务器，部署简单）
b、免费

###1.1 搭建步骤
####1.1.1 去github上创建一个新的仓库，命名为username.github.io

####1.1.2 克隆该仓库
``` bash
$ git clone https://github.com/username/username.github.io
```

####1.1.3 Hello World
``` bash
$ cd username.github.io
$ echo "Hello World" > index.html
```
####1.1.3 Demo完成
只需启动浏览器，输入username.github.io即可访问
