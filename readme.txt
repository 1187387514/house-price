kaggle房价预测比赛的源码；
此文件特征工程对定类的feature进行了one-hot的处理，对连续值进行了normalize的处理。
模型上使用了lightgbm，模型调参也比较粗。
优化上还有很多的方向，如：
1、提取新的特征
2、使用cross validation和grid search是模型的调参更精细。
3、增加使用的模型，再进行模型的esemble。
