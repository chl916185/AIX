# AIX
Notes and paper reports for machine learning.

机器学习笔记与论文阅读报告

------

**说明**

除论文报告是用英文书写外，其余笔记都是中文形式。所有的笔记和论文报告都提供markdown和pdf两种文件格式，各有优缺点如下：

* markdown文件的阅读体验更好，但不适合在线观看，因为部分文本和公式可能无法正常显示；
* pdf文件适合在线阅读，但是加载较慢，另外一些链接无法正常点击，动图也无法显示；

各文件夹的主题如下：

* **相关数学基础**：一些与机器学习相关的数学知识的整理，一般不会涉及详细的原理推导和解释；
* **机器学习基础**：介绍机器学习的基本概念和基本理论；
* **统计学习模型**：经典统计学习模型的原理介绍，内容比较基础；
* **深度学习基础**：深度学习中基本方法和原理的介绍，一般不涉及具体领域的具体方法；
* **论文报告**：相关论文的总结和报告，以近几年深度学习方面的文章为主，包括一部分具体研究领域的研究方法总结。

------

**传送门**

这里提供pdf文件的链接，markdown文件可以在相应路径下的“markdown”文件夹中找到。



* **相关数学基础**

**线性代数与矩阵理论**：

[**线性代数基本概念汇总**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E7%BA%BF%E6%80%A7%E4%BB%A3%E6%95%B0%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5%E6%B1%87%E6%80%BB.pdf)

[**概念解析_瑞利商**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E6%A6%82%E5%BF%B5%E8%A7%A3%E6%9E%90_%E7%91%9E%E5%88%A9%E5%95%86.pdf)

**凸优化理论**：

[**凸优化的基本介绍**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E5%87%B8%E4%BC%98%E5%8C%96%E7%9A%84%E5%9F%BA%E6%9C%AC%E4%BB%8B%E7%BB%8D.pdf)

[**理解拉格朗日对偶**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E7%90%86%E8%A7%A3%E6%8B%89%E6%A0%BC%E6%9C%97%E6%97%A5%E5%AF%B9%E5%81%B6.pdf)

[**理解KKT条件**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E7%90%86%E8%A7%A3KKT%E6%9D%A1%E4%BB%B6.pdf)

**概率论**：

[**理解贝叶斯公式**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E7%90%86%E8%A7%A3%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%85%AC%E5%BC%8F.pdf)

[**理解贝叶斯先验与后验**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E7%90%86%E8%A7%A3%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%85%88%E9%AA%8C%E4%B8%8E%E5%90%8E%E9%AA%8C.pdf)

[**浅谈频率学派与贝叶斯学派的区别**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E6%B5%85%E8%B0%88%E9%A2%91%E7%8E%87%E5%AD%A6%E6%B4%BE%E4%B8%8E%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%AD%A6%E6%B4%BE%E7%9A%84%E5%8C%BA%E5%88%AB.pdf)

[**最大似然估计与最大后验估计**](https://github.com/KveinXu/AIX/blob/master/%E7%9B%B8%E5%85%B3%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/pdf/%E6%9C%80%E5%A4%A7%E4%BC%BC%E7%84%B6%E4%BC%B0%E8%AE%A1%E4%B8%8E%E6%9C%80%E5%A4%A7%E5%90%8E%E9%AA%8C%E4%BC%B0%E8%AE%A1.pdf)



* **统计学习模型**

**线性判别分析**：

[**LDA和QDA的分类原理**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/LDA%E5%92%8CQDA%E7%9A%84%E5%88%86%E7%B1%BB%E5%8E%9F%E7%90%86.pdf)

[**LDA的降维原理**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/LDA%E7%9A%84%E9%99%8D%E7%BB%B4%E5%8E%9F%E7%90%86.pdf)

**决策树**：

[**决策树及对应算法原理**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/%E5%86%B3%E7%AD%96%E6%A0%91%E5%8F%8A%E5%AF%B9%E5%BA%94%E7%AE%97%E6%B3%95%E5%8E%9F%E7%90%86.pdf)

**支持向量机**：

[**SVM基本原理**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/SVM%E5%9F%BA%E6%9C%AC%E5%8E%9F%E7%90%86.pdf)

[**另类解读SVM—从损失函数说起**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/%E5%8F%A6%E7%B1%BB%E8%A7%A3%E8%AF%BBSVM%E2%80%94%E4%BB%8E%E6%8D%9F%E5%A4%B1%E5%87%BD%E6%95%B0%E8%AF%B4%E8%B5%B7.pdf)

[**支持向量回归（SVR）原理介绍**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/%E6%94%AF%E6%8C%81%E5%90%91%E9%87%8F%E5%9B%9E%E5%BD%92%EF%BC%88SVR%EF%BC%89%E5%8E%9F%E7%90%86%E4%BB%8B%E7%BB%8D.pdf)

**集成学习**：

[**集成学习概览_Bagging与Boosting**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/%E9%9B%86%E6%88%90%E5%AD%A6%E4%B9%A0%E6%A6%82%E8%A7%88_Bagging%E4%B8%8EBoosting.pdf)

[**随机森林原理介绍**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/%E9%9A%8F%E6%9C%BA%E6%A3%AE%E6%9E%97%E5%8E%9F%E7%90%86%E4%BB%8B%E7%BB%8D.pdf)

[**AdaBoost算法原理详解**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/AdaBoost%E7%AE%97%E6%B3%95%E5%8E%9F%E7%90%86%E8%AF%A6%E8%A7%A3.pdf)

[**梯度提升与GBDT原理解析**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/%E6%A2%AF%E5%BA%A6%E6%8F%90%E5%8D%87%E4%B8%8EGBDT%E5%8E%9F%E7%90%86%E8%A7%A3%E6%9E%90.pdf)

[**XGBoost原理解析**](https://github.com/KveinXu/AIX/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%A8%A1%E5%9E%8B/pdf/XGBoost%E5%8E%9F%E7%90%86%E8%A7%A3%E6%9E%90.pdf)



* **深度学习基础**

**优化方法**：

[**SGD及其变体**](https://github.com/KveinXu/AIX/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E5%9F%BA%E7%A1%80/pdf/SGD%E5%8F%8A%E5%85%B6%E5%8F%98%E4%BD%93.pdf)

[**深度学习中的标准化操作_BN与GN**](https://github.com/KveinXu/AIX/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E5%9F%BA%E7%A1%80/pdf/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E4%B8%AD%E7%9A%84%E6%A0%87%E5%87%86%E5%8C%96%E6%93%8D%E4%BD%9C_BN%E4%B8%8EGN.pdf)

**生成对抗网络（GAN）**：

[**GAN原理笔记**](https://github.com/KveinXu/AIX/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E5%9F%BA%E7%A1%80/pdf/GAN%E5%8E%9F%E7%90%86%E7%AC%94%E8%AE%B0.pdf)



* **论文报告**

**Image Classification**:

[**后ResNet时代图像分类方法**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/%E5%90%8EResNet%E6%97%B6%E4%BB%A3%E5%9B%BE%E5%83%8F%E5%88%86%E7%B1%BB%E6%96%B9%E6%B3%95.pdf)

(*including: ResNet, Pre-act ResNet, Xception, Inception-ResNet-v2, ResNeXt, DenseNet*)

**Object Detection**:

[**目标检测方法总结**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/%E7%9B%AE%E6%A0%87%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.pdf)

(*including: R-CNN, Fast R-CNN, Faster R-CNN, R-FCN, FPN, Mask R-CNN, Cascade R-CNN, SSD, DSSD, FSSD, DSOD, YOLOv1, YOLOv2 & YOLO9000, YOLOv3, RetinaNet, RefineDet, RFBNet, M2Det*)

**Action Recognition**:

[**动作识别总结**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/%E5%8A%A8%E4%BD%9C%E8%AF%86%E5%88%AB%E6%80%BB%E7%BB%93.pdf) 

(*including: Two-stream, LRCN, Two-stream Conv pooling & Two-stream + LSTM, C3D, F_STNet, two-stream fusion, ST-ResNet, TSN, I3D, Res3D, P3D, 3D ResNeXt, R(2+1)D, ARTNet, Non-Local, StNet, CNN+GRU, TRN, S3D, ECO*)

**Few-shot Learning**:

[**Few-shot三大经典方法小结**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/Few-shot%E4%B8%89%E5%A4%A7%E7%BB%8F%E5%85%B8%E6%96%B9%E6%B3%95%E5%B0%8F%E7%BB%93.pdf) 

(*including: Siamese Network, Matching Network, Prototypical Network*)

**Meta Learning**:

[**浅析MAML算法**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/%E6%B5%85%E6%9E%90MAML%E7%AE%97%E6%B3%95.pdf)

**Others**:

[**Capsule胶囊网络介绍**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/Capsule%E8%83%B6%E5%9B%8A%E7%BD%91%E7%BB%9C%E4%BB%8B%E7%BB%8D.pdf)

[**从采样定理思考CNN泛化性能**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/%E4%BB%8E%E9%87%87%E6%A0%B7%E5%AE%9A%E7%90%86%E6%80%9D%E8%80%83CNN%E6%B3%9B%E5%8C%96%E6%80%A7%E8%83%BD.pdf)

[**反思ImageNet预训练**](https://github.com/KveinXu/AIX/blob/master/%E8%AE%BA%E6%96%87%E6%8A%A5%E5%91%8A/pdf/%E5%8F%8D%E6%80%9DImageNet%E9%A2%84%E8%AE%AD%E7%BB%83.pdf)