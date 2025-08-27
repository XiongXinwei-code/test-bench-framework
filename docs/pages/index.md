---
layout: page
title: Test Bench Framework
permalink: /
---

# 欢迎来到Test Bench Framework

在这里您将学习到关于如何使用“Test Bench Framework”开发测试序列。

![assets/img/SequenceEditor.png](assets/img/SequenceEditor.png)

## 前言

**Test Bench Framework是参考Test Stand的功能设计出来的一款工具软件，TS对开发FCT和EOL的开发和调试效率提升非常大。**

不过下面这几个原因导致了我们需要自己开发一款类似的测试序列管理工具：

1. 软件成本：LV开发的应用程序部署是免费的，但是最便宜的TS部署版本都要将近6kRMB

2. 过度设计：TS软件过于复杂其中很多功能在简单的需求中使用不到，但是由于这些功能的存在导致学习难度增加

3. 并行：在TS中很难实现并行测试或者让这些并行的测试可视化

4. 测试引擎接口：不熟悉.net框架的工程师可能无法理解如何使用

5. 部署：部署TS过程非常复杂

6. 测试序列编辑器：界面元素过多

7. 很难实现复杂的多线程模型，或者说实现的过程很复杂

