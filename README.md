\# 泰坦尼克号乘客生存分析



\## 项目简介

基于 Kaggle 泰坦尼克号数据集，探索影响乘客生存的关键因素，

并构建一个基线分类模型进行预测。



\## 数据来源

Kaggle Titanic: Machine Learning from Disaster (train.csv, 891条记录)



\## 分析流程

1\. 数据加载与初步观察

2\. 数据清洗：处理 Age、Embarked 缺失值，丢弃 Cabin/Ticket

3\. 特征工程：提取 Title、创建 FamilySize 和 IsAlone

4\. 探索性数据分析：性别、舱位、年龄、家庭规模与生存率的关系

5\. 建模：逻辑回归基线模型，准确率约 78%-80%



\## 主要发现

\- 整体生存率约 38%

\- 女性生存率显著高于男性

\- 头等舱生存率最高，三等舱最低

\- 家庭规模 2-4 人的生存率最高

\- 称呼（Title）中 Mrs 和 Miss 的生存率明显高于 Mr



\## 运行方式

pip install -r requirements.txt

jupyter notebook notebooks/titanic\_analysis.ipynb

