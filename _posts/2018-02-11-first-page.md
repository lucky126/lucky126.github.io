---
layout: post
title: 开篇小记
key: 20180211
tags:
  - 开篇
  - github
lang: zh-Hans
---

## 开篇小记

经过两个晚上不懈的努力，终于折腾出来一个可以使用的空间。也总算让自己在github这个知名的网站上开了一个属于自己的空间。
<!--more-->
下面总结一下这两天的故事

首先，最近看过同事在github上的部落格，觉得内容很好，并且也很受启发，也想将自己的各类空间汇总合并到这里。

于是乎，就开始搜寻github.io上如何建立个人的博客。犯的第一个错误是，没有注意到github的规定是github.io的二级域名必须是用户名。

其次是网上的教程太多，太五花八门了，说的天花乱坠的，但是看同事的部落格还是相当简单的。所以呢，第一天晚上2个多小时几乎算是白折腾了一圈。从建立了，调整了，删除了，反正是尝试了一圈。不过也算留下了一些经验。

第二天总结了一下第一天的经验和问题，确定解决方案：

1. 从网上找一个jekyll的[模板网站](http://jekyllthemes.org/)，从中选择一个适合自己的模板。
2. 将这个模板fork到自己repo下。
3. 将fork过来的repo改名成为name.github.io。
4. 通过
```
git clone git@github.com:lucky126/lucky126.github.io.git
```
命令，将代码拉到本地
5. 现在可以在本地任意修改内容了，然后commit and push就好了。

到此为止，空间终于算建立完毕了。