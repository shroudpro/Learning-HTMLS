# 交互学习 HTML 页面总览

本目录收录 10 个独立的交互学习页面。每个 demo 都以自己的 **index.html** 作为入口；如页面需要额外的模型、贴图、脚本或样式，请放在对应 demo 子目录中，避免不同页面的资源互相覆盖。

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

## 目录约定

- 每个子目录是一个独立页面，入口文件统一命名为 **index.html**。
- 若需要外部资源，在页面自己的目录下新增 **assets/**，例如 **ml-ch01-intro/assets/models/scene.glb**。
- HTML 中使用相对路径引用同一页面的资源；.gltf 所引用的贴图和二进制文件也要一并保留原有相对目录。
- GitHub Pages 的路径区分大小写。目录名、文件名和 HTML 中的引用必须完全一致。

#
