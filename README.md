# Big Data and Cloud Computing

> [!NOTE] 
> 南京工程学院计算机工程学院2023-2024春学期大数据与云计算技术课程（0809702984）




### 实验一：代码云平台操作基础

目标：掌握GitHub代码云平台基础操作。

实验内容：
- 创建GitHub账号
- 创建Repo
- 基于MarkDown编写README.md
- 提交代码
- Fork&Star Repo
- 基于Repo改写main/test.py

### 实验二：机器学习云平台基础操作

目标：掌握Kaggle机器学习云平台基础操作。

实验内容：
- 创建Kaggle账号
- 新建Notebook
- 新建Dataset
- 编写并运行Python代码，实现：
  - 快速排序
  - 九九乘法表
  - Fibonacci数列

### 实验三：云平台自然语言处理技术

目标：了解在云平台下的自然语言处理技术，熟悉Gensim自然语言处理工具。

实验内容：
- 新建Corpus并剔除Stopwords
- 创建自然语言模型（例如LSI，TF-IDF）
- 初始化相似度查询结构
- 相似度查询

参考：
- https://radimrehurek.com/gensim/auto_examples/core/run_similarity_queries.html
- https://radimrehurek.com/gensim/auto_examples/core/run_core_concepts.html

### 实验四：云平台词向量数据可视化方法

目标：了解在云平台下的词向量数据可视化方法

实验内容：
- 加载/创建word2vec词向量模型，可根据Corpus，自由选择N个目标词，例如 `keys = ['game', 'terrorist', 'farmers', 'mind']`
- 根据词向量计算相似度，并输出目标词的Top-K相关词
- 基于t-SNE算法将词向量降维
- 基于matplotlib将目标词和对应Top-K相关词进行可视化展示

提示：
- `from gensim.test.utils import datapath`，`datapath('word2vec_pre_kv_c')`
- `from gensim.models import KeyedVectors`，`KeyedVectors.load_word2vec_format`，`most_similar(word, topn=30)`
- `from sklearn.manifold import TSNE`

参考：
- https://radimrehurek.com/gensim/models/keyedvectors.html
- https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html
- https://matplotlib.org/

例子：
![Image text](https://github.com/cuishicheng/Big-Data-and-Cloud-Computing/blob/main/main/example.png =500x500)

### 实验五：Sentiment Analysis of IMDB Movie Reviews 云平台编程实战1

目标：基于Kaggle云平台，实现IMDB影评情感分析

### 实验六：Sentiment Analysis of IMDB Movie Reviews 云平台编程实战2

目标：基于Kaggle云平台，实现IMDB影评情感分析
