# JData
京东算法大赛

排名198，模型框架来源于知乎
[JDATA京东算法大赛入门(score0.07+时间滑动窗口特征＋xgboost模型) - 知乎专栏](https://zhuanlan.zhihu.com/p/26177617)

选用的特征不同，原因有两个：
客观原因：电脑内存有限，只有4G，没办法用时间滑动窗口。
主观原因：我认为应该把每一次的购买行为视为研究对象，比如某用户在5号和15号购买了同一件商品，5号之前的互动行为应该对15号这次购买没有影响。

