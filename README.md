# Document-Classification-of-20-newsgroup

## 20news 分类项目说明 ##

### 0. 版本修改提升 ###
  version1.0 文件夹为初版探索
  version2.0 为提升版本文件
  2.0 版本 机器学习各分类器 和深度学习模型准确率均较第一版本有明显提升

### 1. 文件组成 ###
    final_report.pdf 为本项目报告，包括项目说明，具体实施，结果分析

    ML_report.ipynb 为文本分类机器学习算法代码实施，依赖于sklearn
  
    DL_report.ipynb 为文本分类深度学习算法代码实施，依赖于sklearn，Keras
	
	plot_show.ipynb 为部分作图内容


### 2. 环境要求 ###
   本项目依赖于以下python数据库：

    * sklearn 0.19 机器学习框架
    
    * tensorflow 1.4 深度学习框架
    
    * Keras 2.13 基于tensorflow 的深度学习高级API封装框架
    
    * xgboost 0.7 依赖于梯度提升算法的机器学习库
    
    * gensim 3.2.0 python 中用以训练Word2Vec的库
    
    * 数据处理及可视化依赖于 numpy, matplot，seaborn
   
	ipynb文件运行环境：

    * Anaconda3 Python3.6
    
       

### 数据来源 ###
    使用的数据集包括20newsgroup数据集及text8语料数据集，下载地址为：
    

 - [20newsgroup](http://www.qwone.com/~jason/20Newsgroups/20news-bydate.tar.gz)
 - [text8](http://mattmahoney.net/dc/text8.zip)

### 项目运行###
    在本地cpu环境下可运行ML_report;
    深度学习DL_report 依赖于aws虚拟主机 K80显卡运行，Word2Vec词向量运行时长约2分钟，神经网络训练每epoch时长约100s，30个epoch训练时长小于1h；


### 结果提升：###

通过结构优化和参数调整，获得：

#### - 机器学习 最优分类准确率由81.3%提升至82.47%
#### - 深度学习 最优分类准确率由70.32%提升至85.38%
