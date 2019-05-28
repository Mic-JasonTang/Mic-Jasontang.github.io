---
title: Adaboost 算法介绍
date: 2019-05-28 15:57:05
categories:
- Interview
- Machine Learning
tags: 
- ML
- Adaboost
---

- 作者：鲁力
- 原文：https://github.com/datawhalechina/Daily-interview/tree/master/machine-learning			
- 联系方式：jieyuhuayang@foxmail.com


## 1. Adaboost简介

### 1.1 集成学习（ensemble learning）背景介绍

集成学习（ensemble learning）通过构建并结合多个学习器（learner）来完成学习任务，通常可获得比单一学习器更良好的泛化性能（特别是在集成弱学习器（weak learner）时）。  

目前集成学习主要分为2大类：  

一类是以bagging、Random Forest等算法为代表的，**各个学习器之间相互独立、可同时生成**的并行化方法；

一类是以boosting、Adaboost等算法为代表的，**个体学习器是串行序列化生成的、具有依赖关系**，它试图不断增强单个学习器的学习能力。
<!-- more -->

[阅读更多](https://blog.csdn.net/q361239731/article/details/90645040)