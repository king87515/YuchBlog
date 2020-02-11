---
title: Git+Hexo-架設個人靜態網站
date: 2020-02-10 22:21:19
tags:
- Tool
category:
- Tool
---

## 前言
因為心血來潮，想說是時候該架設自己的網站了，可以記錄自己一些學習心得，在建立環境的時候也是反反覆覆重建了好多次嗚嗚，當然最後還是順利的建完了。

接下來就開始介紹 hexo 的基本安裝，並且架設在自己的github上。

環境：mscOS mojave (當然windows也是可以)

## Github repo設定 & Hexo搭建
設置github page有兩種方式：
1. 以 ```bash
<user_name>.github.io``` 為專案名稱，利用 master branch 建構，這樣生成的網址將會是 ```bash
https://<user_name>.github.io```
2. 以自訂專案名稱 ```bash<repo_name>``` 利用 gh-pages banch 建構，，這樣生成的網址將會是 https://<user_name>.github.io/<repo_name>