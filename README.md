# XGBoost-CatBoost算法性能对比
## 数据集介绍

本项目使用XGBoost和CatBoost对Kaggle的航空信息晚点数据集进行建模，以对比这两种算法在该数据集上性能的差异。

## 代码介绍
1. 本项目先对数据集进行了数据预处理、抽样、以及其他探索性分析。
2. 接着，使用Sklearn中model_selection模块下的GridSearchCV来对两个算法中的一些超参数实现网格搜索调参。
3. 然后，使用两种算法的最优超参数在数据集中训练。
4. 最后，综合对比两种算法的优劣。


## 依赖
运行代码需要安装以下依赖项：
1. Python 3
2. pandas
3. numpy
4. scikit-learn
5. xgboost
6. catboost

