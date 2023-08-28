# ***三大树模型的简单应用——基于Python***

本仓库主要介绍在数学建模中关于`XGBoost`、`Catboost`以及`LightGBM`的简单应用，三大树模型不仅在回归和分类上有着比传统统计学习方法更高的精度，还可以用于研究特征的重要性、探索分类规律等，可以说是数学建模中最好用的神器。

本部分内容非常基础，全都是调用相关库的`Scikit-Learn`接口，因此上手简单，欢迎学习交流。

如果您安装了Git，请直接在任意位置使用命令Clone本仓库内容：

```
git clone https://github.com/Jack-TanXin/Forest-and-ML.git
```

您在使用代码前需要下载四个重要的库，命令如下：

```
!pip install xgboost
!pip install catboost
!pip install lightgbm
!conda install python-graphviz -y
```