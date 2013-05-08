---
layout: post
title: "moodle平台安装及其环境安装"
date: 2013-05-07 21:44
comments: true
categories: moodle 网络课程管理系统
---
##概述
>
> Moodle是模块化面向对象的动态学习环境，由澳大利亚教师Martin Dougiamas基于建构主义教育理论而开发的课程管理系统，是一个免费的开放源代码的软件，目前在各国已广泛使用。<br />
>由于Moodle是用php进行开发的web软件，所以安装Moodle需要相应的web服务器、数据库和php运行程序。针对于没有使用过php的人来说，安装moodle平台还是有点小麻烦的，由此在这里我简要介绍一下Moodle平台的安装过程。
>

##安装过程

1. ###xampp安装
> **注**：您的电脑已经安装apache+mysql+php的用户可以不用浏览改过程。
>
> **声明**：xampp是apache+mysql+php的集成安装包。
>
> ####安装步骤
>>+ 下载xampp软件
	>>>
	>>> 可以到[apachefriends网站](http://www.apachefriends.org/zh_cn/xampp.html)上查找相应的软件。(大部分人都使用windows系统，所以该文章选择适用于windows的xampp进行讲解)
	>>>	
>>+ 安装过程
	>>> 方法 A：使用安装包进行安装
	>>> ![](http://www.apachefriends.org/images/1729.jpg) <br /> 
	>>> 
	>>> 安装过程结束后，您会在 开始/程序/XAMPP 菜单下找到 XAMPP。您可以使用 XAMPP 控制面板来启动/停止所有服务或安装/卸载所有服务。<br />
	>>> ![}(http://www.apachefriends.org/images/1734.jpg) <br/>
	>>> **注**：详细步骤参考[XAMPP for Windows](http://www.apachefriends.org/zh_cn/xampp-windows.html#1735)

2. ###Moodle安装
> ####安装步骤
>>1. 下载Moodle软件
	>>> 强烈建议到[官方网站](https://moodle.org/)下载最新版本的Moodle程序,
	>>> 不要到国内的一些杂牌网站上下载所谓的汉化版。
	>>> 目前最新版本是Moodle2.5beta版,但是建议下载Moode2.4.3稳定版本，下载链接是[Moodle2.4.3下载](http://download.moodle.org/download.php/moodle/moodle-latest.tgz)
>>2. 将解压的Moodle文件夹放到web服务器根目录
	>>> **注**：如果您是按照过程1安装的xampp软件的话，web服务器根目录是在C:xampp/htdocs/文件夹下，所以把moodle文件夹拷贝到该目录即可。
	>>>![](https://raw.github.com/yanzheli/yanzheli.github.com/source/out_images/moodle_url.jpg)
>>3. 浏览器中打开[http://localhost/moodle](http://localhost/moodle)
	>>> 如果您是第一次打开该页面则会出现安装页面，选择中文进行安装（zh_cn）.<br />
	>>>![]()
