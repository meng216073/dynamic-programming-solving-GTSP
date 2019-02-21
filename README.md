# 问题描述

**广义旅行商问题：**给定一个加权图G=(V, E,W)，其中图中的边上有权值（所有权值为正）。给定一个源顶点s，和一个目标顶点点t，以及一个包含k个顶点的查询集合Q={vi1,vi2,…,vik}，其中k<=5。要求设计一个动态规划算法计算从s到t并且经过集合Q中所有顶点的最短路径。

测试数据集来自于http://snap.stanford.edu/data/roadNet-CA.html。这个数据是加利福利亚州的公路网络，包含1,965,206个节点和2,766,607条边。

这个问题分为两部分，第一部分是理由动态规划求解GSTP问题。第二部分在有向有环加权图中求节点对的最短路径。

详细解析部分见explanation文件夹。