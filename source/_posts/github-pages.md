---
title: github个人主页和项目主页
---
本文介绍下github个人主页以及项目主页的搭建方法。

## 1.github个人主页
优点：
a、简单（不需自行搭建服务器，部署简单）
b、免费

### 1.1 搭建步骤
#### 1.1.1 去github上创建一个新的仓库，命名为username.github.io

#### 1.1.2 克隆该仓库
``` bash
$ git clone https://github.com/username/username.github.io
```

#### 1.1.3 Hello World
``` bash
$ cd username.github.io
$ echo "Hello World" > index.html
```
#### 1.1.3 Demo完成
只需启动浏览器，输入username.github.io即可访问

### 1.2 实际应用——个人博客
利用github提供的个人主页的功能，可以发挥自己的才华，制作漂亮、强大的个人主页。这里演示用github上流行的hexo框架搭建博客，具体可参考之前一篇博客。

## 2.github项目主页
利用github项目主页的功能，可以为自己的项目写说明、开发等各种文档，如果正好是一个web项目，我们可以直接将web项目的结果已项目主页的方式展示出来。

与个人主页不同的是，项目主页需要将部署代码放到远程一个叫gh-pages的分支上。
``` bash
$ git checkout -b gh-pages
$ git push -u gh-pages
```
示例：
pengfu.github.com/vue-2048

