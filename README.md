# Kaggle Titanic 生存预测项目
## 项目简介
完成Kaggle经典泰坦尼克遇难者生存预测任务，使用逻辑回归搭建基线模型。
## 实施步骤
1. 数据集来自Kaggle官方竞赛，路径适配新版Kaggle `/kaggle/input/competitions/titanic/`
2. 预处理：完成Age、Embarked、Fare缺失值填充，剔除Cabin无用列，对类别特征独热编码
3. 模型：采用LogisticRegression，设置max_iter=500保证收敛
4. 产出submission.csv提交线上评测
## 文件说明
- xxx.ipynb：完整可运行代码笔记本
- submission.csv：线上提交文件
## 本地验证效果
本地划分20%验证集，准确率处于0.78~0.82区间
