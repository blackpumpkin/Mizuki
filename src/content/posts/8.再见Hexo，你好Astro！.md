---
title: 再见Hexo，你好Astro！
published: 2025-11-16
description: 将博客从hexo搬迁至astro
tags: [astro,博客技巧,github]
category: 博客技巧
draft: false
pinned: false
---

时隔一年，工作算是稳定下来了，再次动起了写博客的心，然而看到被我魔改到面目全非的butterfly，想要对博客进行一次大更新，这时看到了Astro框架的Mizuki主题，界面简洁，功能丰富，很适合在摸鱼的时候写文章，于是开始进行博客的搬迁过程。

# 一、安装astro

参考<https://docs.astro.build/zh-cn/install-and-setup/>
在开始-欢迎世界！-教程：搭建一个博客中，按照教程操作。

打开git的控制台，安装astro：npm create astro@latest  或者pnpm create astro@latest
输入y以继续安装程序。
安装完成后会出现名为tasty-transit的文件夹。

启动 astro 开发服务器：npm run dev 或者pnpm dev
如果一切顺利，astro 将在 <http://localhost:4321/> 上为项目提供服务。在浏览器中访问该链接。
在控制台输入ctrl+C退出。

可以选择安装vscode的astro程序，这样就不用每次打开控制台了，在vscode内部输入ctrl+j即可使用内部终端。

# 二、配置Mizuki主题

通过配置文件 astro.config.mjs 自定义博客

参考<https://docs.mizuki.mysqil.com/guide/get-started/>
