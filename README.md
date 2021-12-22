# Assignment-Statistics
 Assignment II in 2021 Fall

**任务要求**

应用回归方法解决一个实际问题

自己选择一个实际问题，收集数据，使用回归方法解决。

注意：所使用的回归方法不限于课堂讲过的线性回归方法，也可以使用其他回归方法，如曲线回归方法，广义回归方法等。

**任务目标**

通过网络收集2017年世界球坛职业球员的数据，并进行如下分析。

1. 对球员的评分和各项能力水平进行**多元线性回归分析**，通过**逐步回归**或**lasso**的方法对变量进行筛选，解决多重共线性的问题，寻找对球员评分影响最大的能力属性，基于此，对球员评分进行预测。

2. 对球员的场上位置和各项能力水平进行**多项logistic回归**，通过**逐步回归**或**lasso**的方法对变量进行筛选，建立模型，对球员的场上位置进行预测。

**方法实现**

本报告的数据分析使用 [R语言](https://www.r-project.org)实现，本报告的编写基于 [RMarkdown](https://rmarkdown.rstudio.com)，代码详见footballplayer.md。

* 多元线性回归：lm函数

* 多项logistic回归：[nnet](https://cran.r-project.org/web/packages/nnet/) 包中的multinom函数

* 逐步回归：step函数

* lasso：[glmnet](https://hastie.su.domains/Papers/glmnet.pdf) 包中的glmnet函数
