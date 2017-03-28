Udacity-ML-nanodegrees,totally 6 project....于3月末毕业，拿到纳米学位
# Udacity Machine Learning Nanodegree Projects
这是完成Udacity ML nanodegree所需的项目集合。有6个项目，简单的项目1到涉及更多的项目3和项目4。每个项目（P1除外）都不不同侧重的ML特定领域：监督，无监督和强化学习还有深度。 回头看，我发现所有的项目（特别是P1和P2）都比较容易，

* [**Project 1: Predicting Boston Housing Prices**]

一个非常简单的项目，熟悉使用numpy和scipy的基本机器学习技术。 它依赖于着名的波士顿房价数据集，可以直接从sklearn访问。 回归问题，监督学习。

A very simple project to get acquainted to working with basic machine learning techniques using numpy and scipy. It relies on the famous Boston houses prices dataset which can be accessed directly from sklearn. Regression problem, supervised learning.

* [**Project 2: Building a Student Intervention System**]

监督学习项目。 该项目的目标是确定可能需要根据考试成绩进行早期干预的学生。
A supervised learning project. The goal of this project is to identify students who might need an early intervention based on their exams' scores. 监督学习项目。 该项目的目标是确定可能需要根据考试成绩进行早期干预的学生。


* [**Project 3: Creating Customer Segments**]

一个无监督的学习项目。目标是确定数据中的客户细分，并为每个客户群提出个性化的产品发货计划。 这个项目比前两个更复杂。 强调：

* 在可视化每个特征的分布后，我们对它们进行变换，使其分布更接近正常。 我们使用基于IQR的Tukey方法检测和去除异常值
* 我们应用PCA转换，并尝试分析和可视化所得到的组件
* 最后，我们通过GMM选择K-Means进行聚类，根据轮廓分数选择最佳的群集编号，并分析这些群集可能代表的客户群
* 最后，我们讨论如何运行

An unsupervised learning project. We analyze a [Wholesale customers dataset](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) from UCI. The goal is to identify customer segments in data and to propose a personalized product delivery schedule for each customer segment. This project is more complicated than the previous two. 

* [**Project 4. Training a Smartcab to Drive**]
在这个项目中，我们训练一个智能代理，开个简单的虚拟城镇。我们需要考虑道路上的其他车辆，交通信号灯和基本转弯规则，并使我们的智能座席及时到达目的地。该项目需要“pygame”GUI编程模块，并没有那么明显的设置过程。我建议用“anaconda”环境安装（尽管我不定期使用它）。

 * 我们使用马尔可夫决策过程（MDP），特别是Q-Learning来描述智能代理发现自己的每个状态的可能动作。我们坚持使用简单的基于Q-Table的算法，无需DQN或策略渐进和研究我们智能代理的不同行为。
 * 我们尝试通过缩小Q-Table大小和调整超参数来优化学习。
 * 最后，我们比较两种动作选择算法：GLIE（贪心学习无限探索）和softmax动作选择。 
 
In this project we train a smart agent to drive a simple virtual town. We need to consider other cars on the road, traffic lights and basic turning rules and to make our smart agent reach the destination in time. The project requires `pygame` GUI programming module with not-that-obvious setup process. I suggest installing it with `anaconda` enviroment (though I don't use it on a regular basis).
