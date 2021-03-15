---
layout: post
title: 三分钟在GitHub上搭建个人博客
categories: github
description: GitHub作为全球最大的程序员交友网站，是一个代码托管平台和开发者社区，开发者可以在Github上创建自己的开源项目并与其他开发者协作编码。
keywords: github
tags: github
---

GitHub作为全球最大的程序员交友网站，是一个代码托管平台和开发者社区，开发者可以在Github上创建自己的开源项目并与其他开发者协作编码。

最近想在GitHub上搭建一个自己的博客，可是搜寻了网上的好多教程都不成功。有的教程偏老，有的教程不适合小白过于复杂。没办法，自己刚入门，捣鼓了半天，总算摸出了一条适合小白搭建博客的方法，下面进入正题：（注意：此方法适合小白）

1.首先，不用多说，得先有一个GitHub账号吧：

![](/images/2.jpg)

填好自己得个人信息（用户名好像不能用汉字）：

![](/images/3.png)

然后点击Create an account.

![](/images/4.jpg)

2.开始搭建博客：

以前GitHub上的项目之类的都是一大堆源代码，对于一个新手来说，看到一大堆源码，只会让人头晕脑涨，不知何处入手。他希望看到的是，一个简明易懂的网页，说明每一步应该怎么做。因此，github就设计了Pages功能，允许用户自定义项目首页，用来替代默认的源码列表。所以，github Pages可以被认为是用户编写的、托管在github上的静态网页。

首先，我们需要新建一个Repositories,Repositories就相当于一个库，存放我们的项目文件。

![](/images/5.jpg)

然后给自己的Repositories取一个名字，注意：名称格式最好为：用户名.github.io

![](/images/6.jpg)

然后点击create repositories.

随后跳转到该库界面,由于我是搭建好的，所以会有项目文件，然后选择Settings

![](/images/7.jpg)

进入settings后，往下拉，找到GitHub pages设置界面

![](/images/8.jpg)

按如图所示选择，注意，选择source之后记得Save，然后点击Choose a theme选择一个博客主题。

![](/images/9.jpg)

然后点击Select theme

到这一步呢，正常来说你就可以看到自己的博客了。在地址栏输入：用户名.http://github.io你就可以访问页面了。

最后修改代码,再用git push即可！