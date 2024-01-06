# XGBoost-CatBoost算法性能对比
## 项目简介

本项目使用XGBoost和CatBoost对Kaggle的航空信息晚点数据集中的flights.csv进行建模，以对比这两种算法在该数据集上性能的差异。
数据集链接为：https://www.kaggle.com/datasets/usdot/flight-delays

## 复现步骤
1. 本项目先对数据集进行了数据预处理、抽样、以及其他探索性分析。
2. 接着，使用Sklearn中model_selection模块下的GridSearchCV来对两个算法中的一些超参数实现网格搜索调参。
3. 然后，使用两种算法的最优超参数在数据集中训练。
4. 最后，综合对比两种算法的优劣。


## 依赖
运行代码需要安装以下依赖项：
1. Python版本: 3.11.4 
2. pandas版本: 1.5.3
3. numpy版本: 1.24.3
4. scikit-learn版本: 1.3.0
5. xgboost版本: 2.0.3
6. catboost版本: 1.2.2

