---
layout:     post
title:      Altium Designer
subtitle:   
date:       2020-03-31
author:     蔡银锚
header-img:
catalog: true
tags:
    - Altium Designer
---

## Altium Designer

- 改变放置的物体的属性，可以通过双机鼠标左键和按tab键进行设置。
- 退出可以使用鼠标右键和esc键
- 导线宽度的设置：tab键 双击导线
- 原理图工作环境设置：工具->设置原理图参数
- 图纸设置：设计->文档选项



##默认电源器件名：

1. 电源地：GND
2. 信号地：SGND
3. 接地：EARTH



## QA

1. 光电元件的贴片封装在哪里？（发光二极管，感光三极管）
2. 滑动变阻器的贴片封装在哪里？



## Library

1. 模型库(*.PcbLib)每个域类型的代表模型
2. 原理图库(*.SchLib)原理图库符号只可以被看做一个指针
3. 集成库(*.IntLib)将源符号，占用空间和其他信息编译成单个文件。
4. 数据库包含两种类型：非版本控制数据库，版本控制数据库(SVN)。

## 设计流程

创建工程->画电路图（网络报表）->元器件封装->整个工程编译无误->导入PCB
