---
title: 上班查寶可夢個體利器 - Poketex
date: 2023-03-11 21:25:36
tags: rust, tui, cli, pokemon
---

## Poektex

一個可以在terminal上跑的寶可夢全國圖鑑

我之前有一段時間做了一個可以在terminal上跑的寶可夢圖鑑，最原本的想法是想在上班的時候正大光明查寶可夢的個體值，因為那個時候剛好在瘋寶可夢對戰，所以就做了這個東西出來

Github連結在這: [ckaznable/poketex](https://github.com/ckaznable/poketex)

不定時會更新，全國圖鑑有增加也會找時間更新資料，之後可能會想在上面直接增加計算機的功能更方便計算xd

## Demo

![demo](https://raw.githubusercontent.com/ckaznable/poketex/master/doc/demo.png "Demo")

截圖是英文的但是實際上使用到中文環境會是顯示中文的資料，如果沒有，那可能啟動的時候帶一下`-l zh`就可以了

## 安裝

可以直接到 [發布頁面](https://github.com/ckaznable/poketex/releases/latest)選對應的下載，然後直接啟動壓縮檔內的`poketex`就可以

```shell
./poketex
```

只是現在要在windows上用的話還有些問題，可能要linux或者使用wsl來使用

## 透過Cargo安裝

因為`poketex`我是用rust開發的，所以也有放到`cargo`上面，如果你有rust的環境那就可以用`cargo`來裝

```shell
cargo install poketex
```

## 操作方法

基本移動可以使用方向鍵還有`hjkl`

更快速的移動可以使用`Page Up`跟`Page Down`一次可以移動四個

因為有刻意把vim的鍵位放進去所以也可以用`G`來直接跳到最後一個，`gg`回到第一個

按下`/`會進入輸入模式然後開啟搜尋input，主要是用名字跟編號來做搜尋，輸入完後可以按`Enter`確定，或者按`ESC`取消輸入模式

最後是按`q`就可以離開圖鑑

## 結語

如果有發現問題可以在github發issue!!
