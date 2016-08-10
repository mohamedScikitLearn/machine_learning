# 1 算法简介
简言之，朴素贝叶斯算法就是应用先前事件的有关数据估计未来事件发生的概率

应用领域：
    1.文本分类：垃圾邮件过滤、作者识别和主题分类等
    2.异常检测：网络入侵、网络异常
    3.身体诊断：根据观察到的症状诊断身体的状况
	
朴素贝叶斯算法的核心思想是在给定现有证据的条件下，给出将发生事件的可能性大小。
值得注意的是，贝叶斯方法利用了所有可以获得的证据来修正预测，所以即使单一特征的影响很小，但当特征量达到一定值时，它们的组合影响也可能会相当大。

---

# 2 实验数据
SMS文本信息:Datasets\sms_spam.csv

---

# 3 模型说明
Naive Bayes 输入一般为分类变量的稀疏矩阵，数值型数据一般利用分位数离散化