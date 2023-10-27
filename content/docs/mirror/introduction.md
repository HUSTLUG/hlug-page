+++
title = "镜像站介绍"
date = 2023-10-27T18:00:00+00:00
updated = 2023-10-27T18:00:00+00:00
draft = false
weight = 1
sort_by = "weight"
template = "docs/page.html"
[extra]
toc = true
top = false
+++

## 写在前面
目前我们的Yogurt镜像站仍旧在热烈开发中，目前不建议任何人员进行除测试外其他应用。如有镜像源需求，建议大家仍旧使用已经成熟且稳定的镜像源：
+ [清华大学TUNA镜像站](https://mirrors.tuna.tsinghua.edu.cn/)
+ [中国科学技术大学镜像站](https://mirrors.ustc.edu.cn/)
+ [南方科技大学镜像站](https://mirrors.sustech.edu.cn/)
+ [上海交通大学思源镜像站](https://mirror.sjtu.edu.cn/)
+ [上海交通大学致远镜像站](https://mirrors.sjtug.sjtu.edu.cn/)
+ [阿里OPSX镜像站](https://developer.aliyun.com/mirror/)
+ [华为开源软件镜像站](https://mirrors.huaweicloud.com/)
+ [腾讯软件源](https://mirrors.cloud.tencent.com/)


## 快速使用
我们的镜像站点位于[https://mirrors.hlug.cn](https://mirrors.hlug.cn)，各镜像的使用方法请参考镜像站内部文档

## 为什么我们要做镜像站
1. 华中地区缺少一个高可用高速的开源软件镜像站
2. HUST校内部分服务器处于内网之中，需要一个对内网开放的镜像站作为下载支持
3. 校内部分同学使用的语言/工具较冷门，难以找到一个合适的国内镜像

## 为什么不使用tunasync之类的镜像工具

>如无必要，勿增实体
> 
> --Occam's Razor

目前清华的tunasync确实已经十分成熟，我们在项目初期也考虑过使用tunasync作为我们镜像源的后端，但是考虑到对镜像的维护，我们想要
接手这个项目的同学，能够在不那么了解配置文件、数据库、后端语言的情况下，使用镜像源管理面板来实现对镜像站的管理。而处理这种问题
的最好方案就是自己重新写一个。

## 目前进度

目前镜像站的主体已经开发完毕，但是未经过时间的检验，在我们测试之后，会尽快上线高可用的生产版本。

