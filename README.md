# paper-records
I will write it down when I finish reading it

|title|keywords|reference|model framework|conclusion|t|
|-|-|-|-|-|-|
|gradient-bounded-coordinate-descent-sequence-regression|Gradient-Bounded Coordinate-Descent|未知|Logistic Regression+L1正则化|证明梯度有界坐标下降方法对预测模型最优子序列搜索过程的优化效果|1902|
|Fast Logistic Regression for Text Categorization with Variable-Length N-grams|Text Categorization,Logistic Regression|KDD2008|N-gram+Sparse Logistic Regression|提出改进的逻辑回归模型对时间序列进行分类并进行对比分析|1903|
|Bounded Coordinate-Descent for Biological Sequence Classification in High Dimensional Predictor Space|Greedy Coordinate-Descent,Sequence Classification,LR,SVM|KDD2011|梯度有界坐标下降+LR/SVM进行对比实验|实验证明应用坐标下降后平后误差率方面更优|1904|
|Comparison of Modern Stochastic Optimization Algorithms|Gradient-based Optimization Algorithms,softMax regression|University of Edinburgh2014|GD/SGD/S2GD/SAG四种方法分别通过逻辑回归和softmax回归实现并对比|大规模问题中,SGD算法更好；S2GD和SAG能提供更高的精度|1904|
|Feature Learning for Activity Recognition in Ubiquitous Computing|Activity Recognition,Feature Learning|Newcastle University|采用PCA和深层信念网络进行特征学习,基于对信号的逐帧经验累积分布的估计替代传感器数据|与启发式选择的特征进行比较来评估特征学习方法的能力，发现自动估计的特征优于经典的启发式特征|1905|
|Recognizing Smoking Gestures with Inertial Sensors on a Wristband|Smoking Gestures Recognition,Mobile Ccomputing,Wearables,IMU|International Conference on Mobile Systems2014|利用惯性测量单元结合人手部动画轨迹识别并区分出吸烟动作,分类方法采用随机森林和条件随机场|实验准确率达95.7%,与BiteCounter和mPuff的对比试验表明该模型准确率很高且可移植性很好|1906|
|基于可穿戴传感器的人体活动识别研究综述|人体活动识别,可穿戴传感器,特征工程,数据处理,机器学习|Journal of Computer Applications2018|介绍活动识别中的原始数据采集、特征提取、特征选择及分类方法，总结了常用的技术以及研究现状|特征工程是活动识别的关键,提取的特征类型等直接影响识别精度;分类器方面,深度学习作为热点也在活动识别中得到应用|1907|
