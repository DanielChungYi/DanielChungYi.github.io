---
title: WSL教學
date: 2022-10-24 01:41:28
tags:
---
# WSL

## Installation
官方詳細教學
https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview

## 好用的工具

Windows terminal

https://www.microsoft.com/store/productId/9N0DX20HK701


## 怎麼跟Windows傳輸檔案

### WSL -> Windows
```
把當前目錄下的foo資料夾丟回桌面
cp -r foo/ /mnt/c/Users/[Username]/Desktop/
```

###  Windows -> WSL

在ubuntu中，可以開啟windows explorer
```bash=
explorer.exe.
```
![](https://i.imgur.com/4X6ijMu.png)
接著你就會了XD

![](https://i.imgur.com/4cYQqcq.png)


## 怎麼使用Linux GUI軟體

要把WSL的畫面丟回來，首先在Windows端要有個server去接WSL丟出來的畫面
第一步要先裝在Windows端安裝 VcXsrv
[下載點](https://sourceforge.net/projects/vcxsrv/)
安裝方式，無腦下一步即可
