---
title: 安装archniri
summary: 关于安装niri
date: 2026-09-01T23:52:31+08:00
lastmod: 2026-09-01T23:52:31+08:00
slug: get-arch-niri
tags:
  - 日记
  - 安装
draft: false
---
这两天购置了一台笔记本电脑，型号为**hyperx omen12**,这是我第一次正式购买笔记本电脑，确实是很开心的。

### 装archniri

在拿到这个笔记本电脑之后，我决定要使用archlinux niri，便着手开始安装。然而，这个型号的笔记本电脑居然貌似以硬件的形式锁定了windows系统，即我在装好Linux后，在BIOS界面并没有显示linux这一选项。这一现象甚至令[Mn](https://github.com/maxlen727)（*可以称为猫娘*）选手也抓耳挠腮，束手无策，在网络上三番搜寻，依旧无果，虽然能够发现与我出现同样问题的网友，可惜都未提供明确的**解决办法**（见下文），在通宵达旦的鼓捣之后，终于发现了解决办法，并顺利在每次重启之后进入grub界面，从而进到arch中。

使用arch时，一开始装了个Nyxniri（shell是Noctalia），虽然说Noctalia更现代，颜值更高，但出现了无法正常打开Vim，快捷键无法自定义绑定等问题，后来就又换成了DMS（*DankMaterialShell*），也挺好用的，非常喜欢。

### 装Bongo Cat

Bongo Cat是一个DMS的插件，作用是在工作区出现一只小猫，跟随你的键盘敲击而敲击，可爱的。但值得注意的是，在跟随Bongo Cat的指引完成一系列操作后，最后需要重启电脑，而不是按其所述注销即可。

### 关于Zen-Browser

将喜欢的网页拖到Zen-Browser的工作区上方可以将其固定到工作区上方，很好用。工作区下方也可以添加新的工作区以实现快速切换不同的工作，也很实用。值得注意的是，利用pacman装的zen并无法设置简体中文，而利用paru在AUR中下载的zen是具备简体中文的。

### HyperX OMEN型号笔记本电脑无法进入grub的解决办法

首先在windows系统中利用浏览器等安装EasyUEFI软件，打开后进入“管理EFI启动项”界面并把Windows Boot Manager给禁用即可。

### 记录一些niri的快捷键

###### 只用于个人纪录，详情还需自己于设置-快捷键中探索

mod+右键 可以缩放窗口

mod+左键 可以移动窗口

mod+sft+v 可以打开剪切板（右上角也可以打开）

mod+t/enter 打开终端，mod+？打开自由小终端

mod+F2 打开设置

mod+z 打开启动器

## 结语

总体而言，这次安装过程收获很多，结果也很令人满意，其中完全少不了[Mn](https://github.com/maxlen727)的指导，在此鸣谢。

***旅客朋友们，下一站见！❤️***
