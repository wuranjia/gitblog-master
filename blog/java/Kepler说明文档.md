<!--
author: Justin
head: 
date: 2021-07-30
title: Kepler说明文档
tags: java
images: http://pingodata.qiniudn.com/cube2.jpg
category: java
status: publish
summary: 如题目，说明Kepler项目，github上的图床挂了，重新搞一下
-->

## Kepler Distributed Service Framework

### [项目地址](https://github.com/Kepler-Framework/Kepler-All)

不仅是RPC
您的服务健康吗？请关注以下体检菜单

![体检菜单](http://www.ranjia.online/blog/img/kepler/target.png)

* 人人都在说，为什么要造轮子 @See[Dubbo](http://dubbo.io/)科普先，ZeroC ICE还在前。巨人的肩膀上才能看的更远。`

* Kepler Style `尽可能隔离框架侵入性。透明代理，我中有你，你中无我。`

![](http://www.ranjia.online/blog/img/kepler/split.png)


`天下代码，合合分分，分分合合。随时切换才能保持正确的姿势。`

* Kepler的上帝视角
![](http://www.ranjia.online/blog/img/kepler/overview.png)

* @See[关于ZooKeeper]() * @See[关于MongoDB(可选)](https://www.mongodb.org/)

* Kepler的角色分工

![](http://www.ranjia.online/blog/img/kepler/workflow.png)

* Service/Client: `服务提供者/服务调用者` * Registry: `注册中心` * @See[Monitor](https://github.com/Kepler-Framework/Kepler-Admin): `数据收集服务, 收集服务运行时状态` * @See[Admin](https://github.com/Kepler-Framework/Kepler-Admin): `服务管理中心, 提供服务治理统一入口(API)`

* @See[快速开始](https://github.com/Kepler-Framework/Kepler-All/wiki/%E5%85%A5%E9%97%A8-%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B) * @See[管理手册](https://github.com/Kepler-Framework/Kepler-Admin) * @See[更多...](https://github.com/Kepler-Framework/Kepler-All/wiki)