---
title: 巴哈動畫瘋觀看紀錄+
date: 2023-05-01 09:15:50
categories:
 - Github Project
tags:
 - browser-extension
 - javascript
---

巴哈動畫瘋的動畫觀看紀錄看起來是有上限，只要看太多舊的紀錄就會被刷掉，而且過太久好像也會被刪掉

對常追動畫然後有時候會想回味的人不太友善，所以做了這個可以把紀錄存在瀏覽器帳號的插件

只要瀏覽器有登入該瀏覽器的帳號，他就會在每一台有登同一個帳號的瀏覽器去同步這個紀錄，理論上紀錄就會一直存在

## 安裝

* [chrome線上應用程式商店](https://chrome.google.com/webstore/detail/%E5%B7%B4%E5%93%88%E5%8B%95%E7%95%AB%E7%98%8B%E8%A7%80%E7%9C%8B%E7%B4%80%E9%8C%84%2B/hpnfakhnfaicfflmgoknjpogleipigdk?hl=zh-TW)

* [Firefox](https://addons.mozilla.org/addon/baha-ani-history/)

## 功能

![demo](https://raw.githubusercontent.com/ckaznable/baha-ani-history/master/doc/demo.png)

* 看過的動畫會用橘色底標註
* 一樣會標註上次看過的集數

## 從Github安裝

或者從github clone下來自己build來裝也可以

[Github](https://github.com/ckaznable/baha-ani-history)

### 需求

因為有用到bundler所以你需要裝nodejs

### Build

有裝nodejs之後就可以下這段指令，之後就會在dist資料夾理了

```shell
npm run build
```

需要注意的是預設build出來的版本是mv3，如果是要給比較舊的瀏覽器裝需要用mv2的版本

```shell
npm run build:v2
```
