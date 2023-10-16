# Homework-Getting Started
## 1)课程笔记
### 生物信息学中的序列比对
#### 1.序列比对
- 序列比对是生物信息学中的一个重要任务，用于将两个或多个生物学序列进行比较，以找到它们之间的相似性和差异性。
- 序列可以是DNA、RNA或蛋白质序列。
- 比对的目的是识别相同的区域、研究进化关系、寻找功能元素等。
#### 2.基本的比对算法
- 全局比对算法（Needleman-Wunsch算法）：用于比对整个序列，保证找到最高的整体相似性。
- 局部比对算法（Smith-Waterman算法）：用于找到两个序列中的局部相似性，适用于寻找特定区域的相似性。
#### 3.BLAST：基本局部比对算法的改进
- BLAST（Basic Local Alignment Search Tool）是一种常用的序列比对工具，用于在大型数据库中查找相似的序列。
- BLAST采用了一种启发式方法，通过寻找邻近词汇（k-tuples）来加速比对。
- BLAST输出包括得分、位分、期望值和原始分数等信息，用于评估比对的质量和相关性。
#### 4.应用
序列比对在生物学研究中有广泛的应用，包括基因识别、蛋白质比对、进化研究、疾病诊断等。

**基因识别**：通过将已知基因与未知序列比对，可以发现潜在的基因编码区域，从而推断新基因。

**蛋白比对**：蛋白质序列比对有助于确定不同物种中相似蛋白质的结构和功能，对于研究蛋白质的进化以及药物设计等领域有重要意义。

**进化研究**：通过比对不同物种的DNA或蛋白质序列，可以研究生物进化的历史，有助于了解不同物种之间的亲缘关系和进化路径。

**疾病诊断**：将患者的DNA序列与已知的致病变异比对，可以确定患者是否患有特定遗传疾病。

## 2)学习计划 - 生物信息学
### I. 编程技能
- **Weeks 1-5:** 学习Linux
  - 学习Linux基本命令行操作
  - 熟悉Linux文件系统和目录结构
  - 实践Linux环境下的文件管理和文本处理

- **Weeks 6-16:** 学习R
  - 学习R语言的基本语法和数据结构
  - 数据可视化技巧和图形制作
  - 数据处理和统计分析基础
  - 实践生物信息学中的R应用

- **Weeks 11-16:** 学习Python
  - 学习Python编程语言的基础知识
  - Python在生物信息学中的应用
  - 编写生物信息学相关的Python脚本

### II. NGS 数据分析
- **Weeks 5-11:** 学习Next-Generation Sequencing（NGS）数据分析
  - NGS技术概述和数据类型
  - 数据预处理和质控
  - 基因组数据分析
  - 转录组数据分析
  - 实际应用和案例研究

### III. 机器学习
- **Weeks 12-16:** 学习机器学习基础和模型
  - 机器学习概念和原理
  - 常见的机器学习算法
  - 数据准备和特征工程
  - 机器学习模型的训练和评估
  - 生物信息学中的机器学习应用
