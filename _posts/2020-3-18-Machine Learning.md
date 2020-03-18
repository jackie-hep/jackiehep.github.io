---
layout:     post
title:      Machine Learning
subtitle:   基本概念和算法
date:       2020-03-18
author:     PengHe
header-img: img/post-bg-ios9-web.jpg
catalog: true
categories: Tech
tags:
    - Machine Learning    


---

#### 机器学习

机器学习的本质就是将输入（非结构化数据/结构化数据，<mark>&sup1;非结构化数据后续将要转化为结构化数据</mark>），按照一定的数学模型（算法）进行训练（<mark>&sup2;如确定线性算法的参数等</mark>），最后形成有效模型，以便后续解决后续输入的预测问题。

机器学习一般分为7个步骤：

	1.收集数据 （非常重要：收集数据的数量和质量决定了预测模型的好坏）
	2.数据准备 （涉及到数据清洗等步骤）
	3.选择模型（在实际工作中，一般要选择多个模型）
	4.训练 （一般人认为这是最重要的一步，实际上1）3）是最重要的）
	5.评估
	6.参数调整
	7.预测（开始使用）

机器学习的训练方法大致可分为三类：

	监督学习---通过人工打标签来帮助机器学习的方式
	非监督学习---没有使用打标签的方式
	强化学习---通过预测结果的回馈，对输入智能的采取行动

#### 算法方面

机器学习到目前已经有几十年的时间了，由于算力等的限制，一直没有发展起来，但是也积累了许多成熟的算法。对不同的输入数据和应用场景可采用不同的算法模型。直到近几年，由于GPU等算力的大幅提高，机器学习重新提上了日程，并迅猛发展。

| 算法                                                         | 训练方式   |
| :----------------------------------------------------------- | :--------- |
| [线性回归](https://easyai.tech/ai-definition/linear-regression/) | 监督学习   |
| [逻辑回归](https://easyai.tech/ai-definition/logistic-regression/) | 监督学习   |
| [线性判别分析](https://easyai.tech/ai-definition/linear-discriminant-analysis/) | 监督学习   |
| [决策树](https://easyai.tech/ai-definition/decision-tree/)   | 监督学习   |
| [朴素贝叶斯](https://easyai.tech/ai-definition/naive-bayes-classifier/) | 监督学习   |
| [K邻近](https://easyai.tech/ai-definition/k-nearest-neighbors/) | 监督学习   |
| [学习向量量化](https://easyai.tech/ai-definition/learning-vector-quantization/) | 监督学习   |
| [支持向量机](https://easyai.tech/ai-definition/svm/)         | 监督学习   |
| [随机森林](https://easyai.tech/ai-definition/random-forest/) | 监督学习   |
| [AdaBoost](https://easyai.tech/ai-definition/adaboost/)      | 监督学习   |
| 高斯混合模型                                                 | 非监督学习 |
| [限制波尔兹曼机](https://easyai.tech/ai-definition/restricted-boltzmann-machine/) | 非监督学习 |
| [K-means 聚类](https://easyai.tech/ai-definition/k-means-clustering/) | 非监督学习 |
| 最大期望算法                                                 | 非监督学习 |

#### 应用场景

IT领域普遍的应用场景主要包含以下，而CT领域应用的场景更多。

	自然语言处理(主要涉及分词、句法分析等)
	语音识别（语音识别技术ASR，语音合成TTS)
	计算机视觉（人脸识别，卷积神经网络，支持向量机）

#### 机器学习的基础

通过上面的描述可知机器学习是建立在大数据的基础之上的。

