myblog-hexo-source
==================

####教程地址：http://zipperary.com/categories/hexo/

* 如果没有安装hexo，先执行npm install -g hexo
* 我的个人博客基于node - hexo
* 执行npm install
* 执行hexo generate , hexo server 后可本地预览： http://localhost:4000
* 执行hexo g -d 推送到github，个人博客地址： http://kingarthas37.github.io

####如何发布文章
* hexo new "my new post"
* 在H:\hexo\source\_posts中打开这个文件（打开方式用“记事本”即可），配置开头。
```bash
title: my new post #可以改成中文的，如“新文章”
date: 2013-05-29 07:56:29 #发表日期，一般不改动
categories: blog #文章文类
tags: [博客，文章] #文章标签，多于一项时用这种格式
---
#这里是正文，用markdown写，使用方法参照我原来的博客[Introduction to markdown](http://zipperary.com/2013/05/22/introduction-to-markdown/)
```
