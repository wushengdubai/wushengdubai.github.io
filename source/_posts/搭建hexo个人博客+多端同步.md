---
title: 搭建hexo个人博客+多端同步
---
#### 0.Hexo的定义
>Hexo 是一个简单地、轻量地、基于Node的一个静态博客框架，可以方便的生成静态网页托管在github和Heroku上。引用Hexo作者 @tommy351

####  GitHub Pages
GitHub Pages 可以被认为是用户编写的、托管在github上的静态网页。由于它的空间免费稳定， 可以用于介绍托管在github上的Project或者搭建网站。

###  1.Hexo的安装
前提：安装好了Node.js

```
sudo npm install -g hexo
```

在桌面上创建一个Blog文件夹，cd到这个文件下：

```
hexo init
```
执行下面命令开启hexo服务器：

```
hexo s
```
此时在浏览器中打开网站[http://localhost:4000](http://localhost:4000),可以看到如下界面
