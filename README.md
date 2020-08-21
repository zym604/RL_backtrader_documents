# 基于强化学习的自动量化交易系统

主要参考项目为pytorch和backtrader。Pytorch是机器学习界使用率第二的python框架，backtrader是目前python写成的程序化交易框架中比较好的一个。在这里我使用二者进行基于强化学习的量化交易，期望训练人工智能学会交易。

(此项目仅用于展示代码运行结果，源码请联系作者VX:yzhu25)

2020-08-21：目前本项目已实现框架自行交易，效果如下图所示：
![image](https://github.com/zym604/RL_backtrader_documents/blob/master/test.gif)
从图中可以看出，随着训练次数（epoch）的增加，本机器学习算法在不断学习如何交易。但因为数据量不足，因子不足等原因，算法的表现十分一般。
