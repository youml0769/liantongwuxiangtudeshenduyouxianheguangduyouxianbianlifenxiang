# 连通无向图的深度优先和广度优先遍历

## 项目描述

本项目实现了一个程序，用于以邻接表或邻接矩阵为存储结构，对连通无向图进行深度优先遍历（DFS）和广度优先遍历（BFS）。程序的基本要求包括：

1. 以邻接表或邻接矩阵为存储结构。
2. 实现连通无向图的深度优先遍历和广度优先遍历。
3. 以用户指定的结点为起点，分别输出每种遍历下的结点访问序列和相应生成树的边集。

## 测试数据

程序使用教科书p168图7.13(a)作为测试数据，确保程序能够正确处理并输出预期的遍历结果。

## 功能实现

1. **存储结构选择**：用户可以选择使用邻接表或邻接矩阵来存储图的结构。
2. **遍历算法**：
   - **深度优先遍历（DFS）**：从指定的起点开始，沿着一条路径尽可能深入地访问图中的结点，直到无法继续为止，然后回溯并尝试其他路径。
   - **广度优先遍历（BFS）**：从指定的起点开始，逐层访问图中的结点，先访问与起点直接相连的结点，然后访问与这些结点相连的结点，以此类推。
3. **输出结果**：
   - 每种遍历方式下，输出结点的访问序列。
   - 输出相应生成树的边集。

## 使用说明

1. 运行程序时，首先选择图的存储结构（邻接表或邻接矩阵）。
2. 输入图的结点数和边数，并指定起点结点。
3. 程序将输出深度优先遍历和广度优先遍历的结果，包括结点访问序列和生成树的边集。

## 注意事项

- 确保输入的图是连通无向图，否则程序可能无法正确执行遍历操作。
- 测试数据应与教科书p168图7.13(a)一致，以确保程序的正确性。

## 贡献

欢迎对本项目进行改进和优化，如有任何问题或建议，请提交Issue或Pull Request。

## 下载链接
[连通无向图的深度优先和广度优先遍历分享](https://pan.quark.cn/s/7f5ed2449775) 

(备用: [备用下载](https://pan.baidu.com/s/1WRG31K2_sIDWDqttdXk0Cg?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
