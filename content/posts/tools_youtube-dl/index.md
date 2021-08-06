---
title: "youtube-dl下载利器"
date: 2021-08-06T10:50:15+08:00
draft: false
description: "通过网站链接下载网站内的视频到本地磁盘"
tags: ["youtube-dl"]
categories: ["tools"]
---
<!--more-->

[youtube-dl  **主页**  ](https://ytdl-org.github.io/youtube-dl/index.html)
[youtube-dl github文档](https://github.com/ytdl-org/youtube-dl/blob/master/README.md#readme)

## youtube-dl 视频下载工具
解决平常看到想要下载保存到本地的视频，然而视频网站一般不提供下载接口，这时候需要	借助工具来完成，而youtube-dl刚好能够解决该痛点。


## youtube-dl 安装
###  MAC 端
Mac系统自带python2，所以无需再安装python
调出终端输入：
```
brew install youtube-dl
或者
port install youtube-dl
```
取决与你电脑安装的工具

### Windows 端

先去官网安装Python3  
Python下载官网：[https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)

下载后，安装的时候记得一定勾选配置环境变量

完成后检测是否安装成功：

按win+R，调出运行，输入cmd回车，再输入

`python`

如果安装成功会显示版本等信息

成功后输入命令：

`exit()`

退出交互端口
装好python后开始安装主角youtube-dl
调用pip安装：
```
pip install youtube-dl
```
回车后会出现下载进度与安装提示

## youtube-dl使用
- 列出支持的网站，终端输入：
    ```
	youtube-dl --list-extractors
    ```
- 下载视频，终端输入：
    ```
	youtube-dl “视频链接”
	如：youtube-dl "www.google.com"
    ```
- 列出所有视频格式，终端输入：
    ```
	youtube-dl -F "视频链接"
	如：youtube-dl -f "www.google.com"
    ```
- 从列表中进行下载
    ```
	youtube-dl -f “视频编码” “视频链接”
	如：youtube-dl -f 1 "www.google.com"
    ```
- 下载到指定目录
    ```
	youtube-dl -o “绝对目录” “视频链接” 
	如：youtube-dl -o '\999\' 'www.google.com'
    ```

## youtube-dl更新
```
pip install --upgrade youtube-dl
```
如[youtube-dl官网所述](https://ytdl-org.github.io/youtube-dl/download.html)，使用[pip](https://pip.pypa.io/en/stable/)是一种安装youtube-dl的方法，该选项可确保您最终安装了最新的可用版本。

要了解youtube-dl的版本与安装位置，可以使用`pip show youtube-dl`命令