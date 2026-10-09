# Demo HTML 页面总览

本目录包含 12 个独立的交互学习页面。每个 demo 都以自己的 **index.html** 为入口。

## 页面索引

### 模式识别与机器学习

| 章节 | 内容概要 | 页面入口 |
| --- | --- | --- |
| 第 1 章 | 绪论 | [打开页面](./ml-ch01-intro/index.html) |
| 第 2 章 | 统计决策理论 | [打开页面](./ml-ch02-statistical-decision/index.html) |
| 第 3 章 | 概率密度函数估计 | [打开页面](./ml-ch03-density-estimation/index.html) |
| 第 4 章 | 线性模型 | [打开页面](./ml-ch04-linear-models/index.html) |
| 第 5 章 | 人工神经网络 | [打开页面](./ml-ch05-neural-networks/index.html) |
| 第 6 章 | 非参数模型 | [打开页面](./ml-ch06-nonparametric/index.html) |
| 第 7 章 | 非监督学习 | [打开页面](./ml-ch07-unsupervised/index.html) |
| 第 8 章 | 特征空间的构建与优化 | [打开页面](./ml-ch08-feature-space/index.html) |

### 通信原理

| 章节 | 内容概要 | 页面入口 |
| --- | --- | --- |
| 第一章 | 绪论 | [打开页面](./comms-ch01-intro/index.html) |
| 第二章 | 确定信号分析 | [打开页面](./comms-ch02-signals/index.html) |

### 信息论

| 章节 | 内容概要 | 页面入口 |
| --- | --- | --- |
| 第一章 | 绪论 | [打开页面](./info-theory-ch01-intro/index.html) |
| 第二章 | 离散信息的度量 | [打开页面](./info-theory-ch02-discrete-information/index.html) |

## 页面与资源约定

- 每个子目录是一个独立页面，入口文件统一命名为 **index.html**。
- 如果页面需要模型、贴图、脚本或样式，将资源放在该 demo 自己的 **assets/** 目录中。
- HTML 使用相对路径引用资源；.gltf 引用的贴图和二进制文件要保持相对目录结构。
- GitHub Pages 的路径区分大小写，目录名、文件名和引用路径必须一致。

## GitHub Pages 地址

单个页面格式：**https://<用户名>.github.io/<仓库名>/demos/<demo目录>/**

仓库首页导航：[index.html](../index.html)。**.nojekyll** 文件放在仓库根目录。
