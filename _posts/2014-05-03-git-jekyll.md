---
layout: post
title: github blog--Jekyll
tagline: 
description:
tags: ["git jekyll"]
---
{% include JB/setup %}
###github blog--Jekyll搭建步骤

####Jekyll是什么？

* Jekyll（发音/'dʒiːk əl/，"杰克尔"）是一个静态站点生成器，它会根据网页源码生成静态文件。它提供了模板、变量、插件等功能，所以实际上可以用来编写整个网站。
####在github上建立blog项目

* 在gituhub dashboard上建立一个新项目，名字为username.github.com。注意username为你github的账号，这个项目一定要用这个名字，这个名字的项目github会自动建立一个username.github.com的页面，将你在这个项目里的文件依照Jekyll摸板进行解析。

####安装Jekyll-Bootstrap
* 其实就是下载Jekyll摸板并上传
* $ git clone https://github.com/plusjade/jekyll-bootstrap.git USERNAME.github.com

* $ cd USERNAME.github.com
* $ git remote set-url origin git@github.com:USERNAME/USERNAME.github.com.git
* $ git push origin master
* 一切正常的话几分钟后就会收到github发来的邮件通知你页面建立完毕。可以通过username.github.com进行访问了。

