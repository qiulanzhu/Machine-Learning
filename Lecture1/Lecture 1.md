## 老师介绍

主讲老师：
Andrew Ng：专研机器学习15年

助教（TAs）：
Paul Baumstarck：主要研究机器学习和计算机视觉
Catie Chang：神经学家，应用机器学习算法以理解人类的大脑
Tom Do：博士，研究计算生物学和人类学习的基本要素
Zico Kolter：首席助教，主要研究机器学习并应用到机器人科学的分支上
Daniel Ramage: 将机器学习算法应用到自然语言处理上
可见机器学习跨学科能力非常强。

## 这门课的三个目标：

1. 理解机器学习令人兴奋的地方。
1. 应用机器算法到感兴趣的问题中。
1. 开始机器学习的研究。

## 前期准备

* 大O的含义
* 数据结构，如：队列、栈、二叉树 
* 编程能力（MATLAB或者Octave），但课程只会有一些编程工作
* 概率统计，如随机变量、随机变量的期望、方差
* 线性代数，如矩阵、向量、矩阵与向量的乘法、矩阵与矩阵的乘法 、逆矩阵、矩阵的特征向量

## 机器学习的定义

* Arthur Samuel(1959)
Field of study that gives computers the ability to learn without being explicitly programmed.
在不直接针对问题进行编程的情况下，赋予计算机学习能力的研究领域。

* Tom Mitchell（1998）
A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T,as measured by P, improves with experience E.
对于一个计算机程序来说，给它一个任务T和一个性能测试方法P，如果在经验E的影响下，
P对T的测试结果得到了改进。那么就说该程序从E中学习。

![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_definition.png)

## 课程总体浏览，四个组要部分

### 第一部分：监督学习（supervised learning）

#### 回归问题（regression problem）
例子：
一片区域房子面积的房子价格的数据。
x轴：房子面积
y轴：房子价格
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_regression.png)

#### 分类问题（classification problem）
例子：一个变量判断肿瘤是否为恶性。
x轴：肿瘤大小
y轴：肿瘤是否为恶性
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_classification1.png)

例子：多个变量判断肿瘤是否为恶性。
x轴：肿瘤大小
y轴：年龄
O：良性
X：恶性
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_classification2.png)

ps:如果你的问题不能在二维、三维甚至任何有限维空间中表示出来，你该怎么办？
支持向量机（support vector machines），可以处理无限种特征。

### 第二部分：学习理论（learning theory）
你为你的学习型算法寻找的训练数据是否已经足够？

### 第三部分：无监督学习（unsupervised learning）
相比于监督学习，没有正确答案。

#### 聚类问题（clustering）
例子一：
基因分组
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_unsupervised1.png)

例子二：
图片轮廓
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_unsupervised2.png)

例子三：
计算机集群、社会网络分析、市场划分、航天数据分析
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_unsupervised3.png)

例子四：
鸡尾酒会问题（cocktail party problem）
对嘈杂的声音分类。

### 第四部分：强化学习（reinforcement learning）
用在你不需要一次决策的情况中。
例子：
控制飞机飞行，一次错误的控制不会让飞机立刻落地，只要一系列还不错的飞行操作，飞机就能正常飞行。
倒立飞行中的飞机。
将条件反射的思维应用其中。
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_reinforcement.png)

助教的作品：
![机器学习定义](http://www.hiqiuyi.cn/Imgs/ml/ml_example.png)
