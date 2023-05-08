---
title: Clash赋予brew新生
author: 张凯博
img: /medias/banner/7.jpg
coverImg: /medias/banner/7.jpg
top: false
cover: false
toc: false
mathjax: true
summary:
  - 使用VPN加速brew下载，告别龟速的brew
tags:
  - Clash
  - brew加速
categories:
  - brew加速
date: 2023-05-06 20:09:33
password:
---
# 前情提要

VPN已经用了很长时间了，经常都是用在访问GitHub，今天在使用brew安装第三方库的时候，经常因为速度下载失败，这时候突然想起能不能用VPN来加速brew下载呢.
使用Clash打开vpn，在使用brew时并没有起到加速作用。在clash中看见一个选项，`复制终端代理命令`。

# 如何使用clash加速brew下载

1.进入clash界面，选择复制终端代理命令

![1683376224885](clash赋予brew新生/1683376224885.png)

2.打开终端，在终端中输入刚刚复制的命令，按下回车即可

![1683376438035](clash赋予brew新生/1683376438035.png)

3.接下来使用brew下载即可

此时会发现brew下载会非常的迅速了，不会因为下载速度而失败了。
