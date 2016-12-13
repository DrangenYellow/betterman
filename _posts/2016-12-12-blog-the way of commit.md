---
layout: post
title: jekyll上传到github的方法
date:   2016-12-12
categories: blog
---

- 直接把根目录上传到github就可以了，只上传_site文件夹下面的也可以，但是这样会导致每次上传都需要把git下所有的文件都替换掉，比较麻烦，所有直接把根目录上传到git，每次新增markdown文章时直接在git文件夹内去生成，然后直接上传就可以了。