---
layout: page
mathjax: true
permalink: /2018/projects/p13/proposal/
---

## 项目题目
基于深度学习的IMDB数据情感分析
### 成员
司恩泽 2120171050
李安民 2120171027
安骄阳 2120170998
邢博文 2120171082
董永银 2120171007
### 问题描述

#### 1、问题背景分析
情感分析（Sentiment analysis）是自然语言处理（NLP）领域的一个任务，又称倾向性分析，意见抽取（Opinion extraction），意见挖掘（Opinion mining），情感挖掘（Sentiment mining），主观分析（Subjectivity analysis）等，它是对带有情感色彩的主观性文本进行分析、处理、归纳和推理的过程，如从电影评论中分析用户对电影的评价（positive、negative），从商品评论文本中分析用户对商品的“价格、大小、重 量、易用性”等属性的情感倾向。
#### 2、问题描述

2.1. 数据准备
数据集取自https://www.kaggle.com/c/word2vec-nlp-tutorial/data，其中包含25000条带标注的IMDB电影评论数据和75000条无标注的评论数据。其中review是评论文本，sentiment是情感分类标注，1代表positive，即评分5分及以上；0代表negative，即评分0-4.9分。
2.2. 模型建立
计划使用多层感知器模型和LSTM分别对评论数据进行情感分析，评估其准确度。
### 项目评估
由于是已经过处理的数据，所以不需过多的净化和预处理。使用不同的评估模型可对其评估结果进行对比，体会其分类效果的差异。
### 项目分工
司恩泽：LSTM模型；安骄阳：多层感知器模型；李安民：数据可视化；邢博文：数据预处理；董永银：报告撰写。