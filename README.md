# 实验3：Jupyter Notebook 基础实践
**实验文件**：`sy3_notebook.ipynb`

---

## 实验目的
1. 熟悉 Python 基础语法，掌握函数定义与算法实现
2. 掌握 Jupyter Notebook 基本使用、单元格模式与内核操作
3. 熟练使用 Pandas 进行数据读取、清洗、筛选与统计分析
4. 使用 Matplotlib 完成数据可视化，实现单图与多图绘制

---

## 实验环境
- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- NumPy

---

## 实验内容
### 1. Notebook 基础操作
- 熟悉 Edit / Command 两种模式
- 掌握常用快捷键
- 理解 Kernel 概念与作用

### 2. Python 基础语法
- 实现选择排序算法 `selection_sort()`
- 编写测试函数 `test()`，支持用户输入、异常处理、结果输出

### 3. 数据分析（Fortune 500）
- 读取 `fortune500.csv` 数据集
- 查看数据结构、列名、数据类型
- 检测并删除 `profit` 为 `N.A.` 的异常数据
- 将 `profit` 转换为数值类型
- 按年份分组计算平均收入与平均利润

### 4. 数据可视化
- 绘制 1955–2005 平均利润变化曲线
- 绘制 1955–2005 平均收入变化曲线
- 绘制均值 ± 标准差对比子图
- 在同一张图中同时绘制平均收入与平均利润
