---
title: Linux Good Apps
author: Xein
categories:
  - 操作系统
  - Linux
tag:
  - Linux
description: 备份的Linux的常用、好用软件列表
---

# Linux-Good-Apps

备份的Linux好用的软件列表

## 一、音乐
- **lx-music（洛雪音乐）**
- **netease-cloud-music-gtk4（网易云音乐三方客户端）**
- **moekoemusic-bin（酷狗音乐三方客户端）**

> Arch linux 下安装：

```bash
yay -S lx-music-desktop-bin
yay -S netease-cloud-music-gtk4
yay -S moekoemusic-bin
```

## 二、文献（文档查看）、笔记、Todo
- **Zotero** 文献查看

> Arch linux 下安装：

```bash
sudo pacman -S zotero-bin
```
插件：
[划句翻译插件-zotero-pdf-translate](https://github.com/windingwind/zotero-pdf-translate)

+ Todo

  + 首先是microsoft todo 的第三方app

    + kuro

      ```bash
      yay -S kuro-bin
      ```

  + 然后是收入到KDE官方的Merkuro

    + Merkuro

      ```bash
      sudo pacman -S merkuro
      ```
+ 笔记
  + Markdown
    + Marknote
    
      ```bash
      sudo pacman -S marknote
      ```
    + Marktext
    
      ```bash
      yay -S marktext
      ```
## 三、游戏

- **Steam**

> Arch linux 下安装：

```bash
sudo pacman -S steam
```

- **Xbox 手柄无线适配器驱动**

因为作者最新的xone驱动无法正常使用，所以使用老版本的驱动

仓库地址

[xow](https://github.com/medusalix/xow)

## 四、主题

- **Catppuccin**

[Catppuccin](https://github.com/catppuccin/catppuccin)

- **Moe**

KDE主题商店下载


## 五、翻译

- 命令行查词软件 Wudao-dict

[Wudao-Dict-官方项目链接](https://github.com/ChestnutHeng/Wudao-dict/)

- 命令行翻译软件 kd

[kd-官方项目链接](https://github.com/Karmenzind/kd)

> Arch linux 下安装：

```bash
# wudao-dict
yay -S wudao-dict-git
# kd
yay -S kd
```

**kd 会比 wd 快很多**(也有可能是因为用的是旧版wd,建议去wd官网使用编译安装)

## 六、绘图

+ drawio 开源思维导图软件（用Electron实现的）无需联网本地跑

```bash
sudo pacman -S drawio-desktop-bin
```

