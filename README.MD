## log
### 2020-03-20 Fri 21:20
**刊物**：
1. 统计研究（1.912）
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=TJYJ 
2. 统计与决策(0.638)
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=TJJC
3. 时代金融(0.051)
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=YNJR
4. 国际金融研究(2.831)
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=GJJR
5. 国际金融(0.615)
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=JRGJ
6. 南方金融(1.391)
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=GDJR 
7. 数量经济技术经济研究(3.165)
   http://navi.cnki.net/KNavi/JournalDetail?pcode=CJFD&pykm=SLJY
8. Econometrics and Statistics
9. Journal of Econometrics
10. International Journal for Theoretical and Applied Statistics


**模型**:
1. 常用的金融风险的模型：波动性方法、VaR模型、灵敏度分析法、一致性风险度量模型、CVaR模型（Condition Value at Risk）条件风险价值（CVaR）模型、条件风险价值（CVaR）模型、条件风险价值（CVaR）模型、谱风险测度(但是该测度实际计算的难度很大，维数过高时，即使转化成线性规划问题，计算也相当困难。)、信息熵方法
2. 混频GARCH-MIDAS模型:宏观，经济不确定新，混频数据
3. KMV模型是现代信用风险度量的重要模型(KMV模型衍生于期权定价理论,利用股权价值、股权价值波动率、企业违约点推算企业资产价值和资产价值的波动率,从而求出违约距离,并得出企业预期违约率)
4. DCC-GARCH模型对股债两市场间的动态相关性建模,并对动态相关系数的时变性和趋势进行探讨分析，VECM模型估计长期均衡方程,对估计结果进行深层次的原因分析。在实证层面,先运用DCC-GARCH模型对股债两市场间的动态相关性建模,并对动态相关系数的时变性和趋势进行探讨分析。

### 2020-03-21 Sat 14:48
《统计研究》：混频、SVM测度金融市场风险、copula模型、logistics模型
《国际金融研究》：DSGE模型、sv-svar
《数量经济技术经济研究》：DSGE模型


### 2020-03-21 Sat 16:16
**信用评估**：LASSO-SVM和Logistic的组合模型进行个人信用评估
针对支持向量机(SVM)不能自动筛选变量的问题，结合 LASSO 算法具有筛
选变量的特点，构造了 LASSO-SVM 模型。LASSO-SVM 模型预测精度高，稳健性差，逻辑回归预测精度较低，解释性强，稳健高，构建了基于最小二乘法的LASSO-SVM 和 Logistic 的线性组合模型，组合模型相对 LASSO-SVM 模型和Logistic 模型而言具有更高的预测精度。

需要信贷数据集（国内个人信贷不易获取）

**信用风险**：基于修正KMV- Copula 模型的组合信用风险度量研究
利用我国ST 和非ST 的上市公司真实数据，对KMV 模型进行修正，引入了基于EGARCH 的KMV 模型计算
单个资产的违约概率。进一步分别采用二元正态- Copula、二元t- Copula 以及二元阿基米德- Copula 包括Gumbel- Copula、
Clayton- Copula 和Frank- Copula 函数对信用资产组合的违约相关性进行建模，研究多资产间的联合违约概率。研究结果表明，修
正的KMV 模型具有合理性和有效性，Clayton- Copula 函数对联合违约概率拟合更好。研究结果有助于商业银行预测各企业的信
用风险大小及可能性，提升应对风险的能力，以维护我国金融市场安全稳健运行。

支持向量机与时间序列方法在ETF风险度量中的应用
选取风险度量指标 VaR 为切入点，比较研究基于支持向量机方法和基于时间序列分析方法在 VaR 值计算上的准确性。以两支 ETF 收盘价数据构造资产组合作为实证研究对象，结合回测检验比较两种方法的优劣，实证发现，在相对较低置信度时（95%，97.5%），时间序列方法较 SVM 方法更保守，时间序列方法倾向于高估真实风险，而基于 SVM 的概率密度估计方法相对倾向于低估真实风险；在相对较高置信度时（99%，99.5%，99.9%），SVM 方法计算 VaR 时更保守，时间序列方法倾向于低估真实风险，而 SVM 方法相对倾向于高估真实风险。 

支持向量机可用于学习理论中的三大问题：模式识别，回归估计，概率密度估
计。目前 SVM 在人脸识别，故障检测，自然语言处理，金融工程等方面应用广泛

风险度量；VaR；时间序列；Copula；支持向量机

### 2020-03-22 Sun 09:09
**realized-garch模型**：

高频数据Realized_GARCH_Copula模型构建及相关性测度：

如何将GARCH类模型框架与纳入高频数据信息的已实现测度相结合成为了国内外学者
研究波动率建模的一个热门研究方向。该模型是Hansen等在2012年提出的基于
GARCH模型引入已实现测度ＲＶ所构建的模型
通过测量方程将己实现测度和GARCH模型的条件波动率相联系起来，并对其进
行了实证研究分析，结果表明了相较于传统的GARCH类模型其能够提高了对波
动预测的能力，因而该模型得到了广泛的认可和研究应用。

Ａｎｄｅｒｓｎ和Ｂｏｌｌｅｒｓｌｅｖ（1998）首次提出了纳入高频数
据信息的已实现波动RV（Realized Volatility,RV），
用５分钟高频采样的数据来计算已实现波动ＲＶ并得出如下结论，即采用５分钟高频数据对
真实波动进行估计能够使精确率和金融市场微观结构噪声达到最佳的平衡。


采用ｔ分布作为残差分布的realized-garch模型，使用四种不同高频数据己实现波动测度
比较了其VaR预测效果。研究金融市场的相关性，研究学者们常用的为Copula方法体系sklar(1959）
最早提出Copula理论，由于Copula函数具有不受边缘分布的限制，并能够准确
反映各变量间的相关模型，处理变量之间的非线性、非对称性和尾部相关等问题
等优势，Copula函数成为了金融市场中金融时间序列间相关性结构建模的标准
化工具，从而它的理论及应用研究得到了研究学者们的广泛关注。Realized GARCH
模型与Copula函数相结合的相关模型在2013年才被提出，相关研究较少。

金融时间序列的波动率和相关性是风险管理、资产组合和资产配置的基础。

选取深证成指和恒生指数作为实证数据，缺乏全面性，后期可考虑
对期货、股指期货、汇率和其他股市指数等进行基于Realized GARCH Copula 模
型的资产组合、资产配置和风险管理的研究，从而证明该模型的适用性。本文仅以t-Copula
函数来拟合深港股市的静态相关结构，并考虑其动态
相关结构和是否存在非线性相关关系，后续的研宄可以尝试将其他类的Copula
函数。随着对己实现测度的研宄的发展，涌现了大量的创新的己实现测度，后
续研究可以尝试纳入其他已实现测度进行研究



