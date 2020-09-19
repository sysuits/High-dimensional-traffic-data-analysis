# 《高维交通大数据模式识别与质量增强》

[^_^]:**数据质量增强**一直是交通大数据分析领域的研究热点。由于检测设备的失灵、数据记录错误和移动检测器渗透率较低等原因，现实中采集到的交通数据往往是**不完整的**，因此有必要对缺失的交通检测数据进行数据质量增强。在最新的相关研究中，基于**张量**的数据质量增强方法被证明是有效和易扩展的，同时张量分解还能够挖掘出高维交通数据中的**隐含模式**，有助于我们更好的理解交通数据和交通系统。

> 本项目对目前高维交通大数据的模式识别与质量增强方法进行了系统性的整理，**主要内容**包括矩阵分解和张量分解的基础知识、张量分解确定性解法、张量分解的贝叶斯优化解法、结合深度学习的非线性张量分解以及张量分解在交通领域的实际应用等。

> **同时本项目公开了主要代码和一些标准数据集，欢迎引用。**

> -----------------------------------------------------------------------------------
:point_right: **data**

- guangzhou_speed_tensor
> 数据描述：广州市路段车速数据集，共214条路段，历时61天，时间窗10min，每天共计144个时间窗，三阶张量大小为214×61×144
- shanghai_speed_tensor/shanghai_flow_tensor
> 数据描述：上海市路段车速、流量数据集，共18条路段，历时28天，时间5min，每天共计288个时间窗，三阶张量大小为18×28×288

> -----------------------------------------------------------------------------------
:point_right: **code**

> -----------------------------------------------------------------------------------
:point_right: **textbook**

> -----------------------------------------------------------------------------------

:point_right: **ppt**

> -----------------------------------------------------------------------------------
:point_right: **paper**【课题组已发表的论文】

- [Chen, Xinyu, Zhaocheng He, and Jiawei Wang. "Spatial-temporal traffic speed patterns discovery and incomplete data recovery via SVD-combined tensor decomposition." Transportation research part C: emerging technologies 86 (2018): 59-77.](https://www.sciencedirect.com/science/article/pii/S0968090X17302966)

> 主要贡献：提出了结合矩阵SVD的张量分解方法，探讨了张量秩的选取问题

- [Chen, Xinyu, Zhaocheng He, and Lijun Sun. "A Bayesian tensor decomposition approach for spatiotemporal traffic data imputation." Transportation research part C: emerging technologies 98 (2019): 73-84.](https://www.sciencedirect.com/science/article/pii/S0968090X1830799X)

> 主要贡献：提出了贝叶斯张量分解方法，研究了不同阶数的张量对数据修复效果的影响

- [Chen, Xinyu, et al. "Missing traffic data imputation and pattern discovery with a Bayesian augmented tensor factorization model." Transportation Research Part C: Emerging Technologies 104 (2019): 66-77.](https://www.sciencedirect.com/science/article/pii/S0968090X18307757)

> 主要贡献：提出了贝叶斯增强张量分解方法，模型具有可解释性




