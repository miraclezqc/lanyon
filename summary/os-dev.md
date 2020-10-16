---
layout: post
title: 操作系统设计
date: 2020-10-16
tag: [summary]
---

操作系统(Operating System, OS)是用户和计算机系统的一个交互界面。

> An interactive envirement that provides an interface for the user and supplied programs, providing a stable and safe envirement, an interface layer to System services and computer hardware.

## 前置知识
### 编程语言
* C/C++
* x86汇编(intel/masm语法)

### 工具
* gcc：用来编译32位C/C++程序
* nasm：用来编译汇编
* GNU ld (Binutils)：链接二进制程序
* GNU Make：自动化编译
* Bochs：调试器
	- 安装问题汇总，<https://blog.csdn.net/geeker_12/article/details/11409009>
	- 编译，<http://bochs.sourceforge.net/doc/docbook/user/compiling.html>
	- 图形界面，<https://virtualizationreview.com/articles/2017/02/08/graphical-programs-on-windows-subsystem-on-linux.aspx>
	- SSH到WSL，<https://superuser.com/questions/1123552/how-to-ssh-into-wsl>
* Oracle VM VirtualBox：模拟器

## 历史和概念
操作系统的历史和基本概念见这个[网页](http://www.brokenthorn.com/Resources/OSDev2.html)。