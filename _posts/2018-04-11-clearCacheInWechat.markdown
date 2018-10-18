---
layout: post
title:  "How to clear cache in WeChat browser"
date:   2018-04-11 16:28:27 +0800
categories: WeChat
---
最近经常接触到需要在微信内置浏览器内打开的项目，常常为它的缓存机制感到头痛。

至于常用的头部“no-cache”在微信内置浏览器中并不好用

因此查询了相关文档，发现了一种很好用的方法：在页面URL中加上时间戳。

`eg."https://baidu.com?v=(timestamp)"`
