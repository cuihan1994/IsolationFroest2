# Isolation-Froest2
Anomaly detection.As a "simple ml" for "beginner"

项目背景-Background
=====

这个项目是延续上一个<a href="https://github.com/SilenceSengoku/IsolationForest">IFroest</a>
的项目。同样是主张实战。

网络上很多资料都是以随机数据集做测试，这其实对很多初学者很不友好。也包括我初学的时候。

所以，我认为应该有比较好的一份实战示例供初学者练习经验，而不是在一次次失败的在coding bug中逐渐劝退。

我很理解，初学者刚开始接触很多新概念的迷茫。所以我做了这个希望对现状有所改变。

关于孤立森林我也正在尝试落地。

所以仅以作此篇为开端，记录自己在异常检测领域思路的一次小梳理。

安装-Install
=====
python version 3.6.5
你需要/You need:

pandas，numpy，sklearn，matplotlib，scipy

> pip install pandas

> pip install numpy

> pip install sklearn

> pip install scipy

> pip install matplotlib



作者-Author & Maintainers
=====
<a href="https://github.com/SilenceSengoku">@Sengoku·Crow·Lu</a>

<a href="https://www.zhihu.com/people/firesnake-67/activities">Sengoku·Crow·Lu's zhihu</a>

参考-Reference
=====
<a href="https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf">Isolation Forest</a>
by Fei Tony Liu, Kai Ming TingGippsland School of Information TechnologyMonash University, Victoria, Australia,2008

<a href="https://github.com/scikit-learn/scikit-learn/blob/master/sklearn/ensemble/_iforest.py">github</a> sklearn iforest_ source code by https://scikit-learn.org

<a href="https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html#sklearn.ensemble.IsolationForest">Sklearn' Isolation Forest Parameter introduction</a>

<a href="https://sklearn.apachecn.org/docs/0.21.3/26.html">Sklearn 中文档</a>

<a href="https://www.zhihu.com/people/firesnake-67/activities">iForest （Isolation Forest）孤立森林</a>by YeZhu - 2017

<a href="https://blog.csdn.net/aiyinsimei/article/details/48003859#0-tsina-1-5960-397232819ff9a47a7b7e80a40613cfe1">Isolation forest的python代码实现</a> by 明日菜心_CSDN 2015-08

<a href="https://blog.csdn.net/ye1215172385/article/details/79762317">IForest主要参数和函数介绍</a>by 夕阳下江堤上的男孩_CSDN 2018-03

