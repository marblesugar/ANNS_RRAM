# Week 1

> TIME: 10.30 - 11.2

> TASK:
>1. 介绍和理解ANNS(blog)
>2. 介绍和理解ANNS(paper)
>3. 跑个ANNS，从实践角度去认识一下ANNS，具体可以抽象成哪些步骤操作，输入输出

>项目背景 :现在论文基于忆阻器的硬件架构主要围绕神经网络(CNN,MLP)加速展开
>
>所以目前定的课题是：研究如何用ReRAM这种存算一体的忆阻器来加速ANNS应用
>
>所以第一步理解ANNS的实现原理，以及上手跑一跑ANNS，同时把《基于忆阻器的近似计算方法》这篇论文看了，看一下如何推理整个过程
>ANNS在算两个向量间距离公式有：Manhattan距离（L1范数），Euclidean距离（L2范数），Cosine距离（1-cosine相似度），角距离，Hamming距离，Dot Rroduct距离
>目前思路：是否可以从这几个距离算法在RRAM上进行加速


