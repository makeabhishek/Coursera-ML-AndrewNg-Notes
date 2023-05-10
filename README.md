**Stanford University 2014 (Wu Enda) Machine Learning Course Chinese Notes**

course address：<https://www.coursera.org/course/ml>

**Machine Learning** (Machine Learning) is the study of how computers simulate or implement human learning behaviors to acquire new knowledge or skills, and reorganize existing knowledge structures to continuously improve their own performance. It is the core of artificial intelligence and the fundamental way to make computers intelligent. Its application pervades all fields of artificial intelligence. It mainly uses induction and synthesis instead of deduction. Over the past decade, machine learning has helped us drive self-driving cars, perform efficient speech recognition, perform efficient web searches, and dramatically improve our understanding of the human genome. Machine learning is so prevalent today that you probably use it dozens of times a day without knowing it. Many researchers also believe that this is the best way to obtain artificial intelligence. In this class, you'll learn the most effective machine learning techniques and gain practice putting them to work for yourself. What's more, you'll learn not only the theoretical foundations, but also the practical techniques that require fast and powerful application of techniques to solve problems. Finally, you'll learn about some of Silicon Valley's best practice innovations utilizing machine learning and artificial intelligence.

This course provides a broad introduction to machine learning, data mining, and statistical pattern recognition. Topics include：

（一）Supervised learning (parametric/nonparametric algorithms, support vector machines, kernel functions, neural networks)。

（二）Unsupervised learning (clustering, dimensionality reduction, recommendation system, deep learning recommendation)。

（三）Best Practices in Machine Learning (Bias/Variance Theory; Innovation Processes in Machine Learning and AI). The course will also use extensive case studies and you will also learn how to use learning algorithms to build intelligent robots (perception, control), understanding of text (**Web** search, anti-spam), computer vision, medical informatics, audio , data mining, and other fields.

This course requires a total of 18 lessons in 10 weeks. Compared with the previous machine learning videos, this video is clearer, and each lesson has **ppt** courseware, which is recommended for learning.

I started to translate the subtitles of this course in the second half of 2014, and wrote the Chinese notes of the course. The notes have been downloaded tens of thousands of times, which should have helped many people, and many people have been helping me. Now I share the **word** and **markdown** manuscripts of the notes with you.

I will put **markdown** notes and course Chinese and English subtitles on **github**, I hope everyone can continue to improve. In order to facilitate the online display of mathematical formulas, the **html** file is viewed online, the formula has been converted into a picture, and the source code of the formula is in the **markdown** file。

**Finally, I want to say to my friends：**
**Gifts of roses, hand a fragrance！**
**On the road of artificial intelligence, you are not alone！**

Huang Haiguang

2018-3-26 夜

微信公众号：机器学习初学者 ![gongzhong](/images/gongzhong.jpg)
知识星球：黄博的机器学习圈子![xingqiu](/images/zhishixingqiu1.jpg)

[我的知乎](https://www.zhihu.com/people/fengdu78/activities)

参考：https://www.coursera.org/course/ml 机器学习公开课

https://mooc.guokr.com/note/12/ [小小人_V](https://mooc.guokr.com/user/2133483357/) 的个人笔记

《统计学习方法》李航
    
《机器学习课》邹博

## 备注：吴恩达老师的深度学习课（deepLearning.ai）的笔记地址：https://github.com/fengdu78/deeplearning_ai_books

-----------------------

文件夹说明：

**docx**：笔记的**word**版本

**markdown**：笔记的**markdown**版本

**html**：笔记的**html**版本

**images**：笔记的图片

**ppt**：课程的原版课件

**srt**：课程的中英文字幕（**mp4**文件需要在百度云下载，大家可以用记事本或者字幕编辑软件来编辑字幕，共同完善，百度云链接：https://pan.baidu.com/s/1h8QjqBlOm0Exh7orm9teMQ 密码：d3we，下载后解压）

**code**：课程的**python**代码（有一部分是国外大牛写的）

机器学习视频下载链接：https://pan.baidu.com/s/1raoOPOg 密码：48m8，包含视频和字幕，下载后解压，建议用**potplayer**播放，此视频与**mp4**一致。

[笔记在线阅读](http://www.ai-start.com/ml2014)

笔记pdf版本下载 ：见**github**根目录。

机器学习qq群：865189078（我们有8个群，加过一个就不需要加了）

-----------------------

# 机器学习教程中文笔记目录

- [第一周](markdown/week1.md)

一、 引言(**Introduction**) 

1.1 欢迎 

1.2 机器学习是什么？ 

1.3 监督学习 

1.4 无监督学习 

二、单变量线性回归(**Linear Regression with One Variable**) 

2.1 模型表示 

2.2 代价函数 

2.3 代价函数的直观理解I 

2.4 代价函数的直观理解II 

2.5 梯度下降 

2.6 梯度下降的直观理解 

2.7 梯度下降的线性回归 

2.8 接下来的内容 

三、线性代数回顾(**Linear Algebra Review**) 

3.1 矩阵和向量 

3.2 加法和标量乘法 

3.3 矩阵向量乘法 

3.4 矩阵乘法 

3.5 矩阵乘法的性质 

3.6 逆、转置

- [第二周](markdown/week2.md)

四、多变量线性回归(**Linear Regression with Multiple Variables**) 

4.1 多维特征 

4.2 多变量梯度下降 

4.3 梯度下降法实践1-特征缩放 

4.4 梯度下降法实践2-学习率 

4.5 特征和多项式回归 

4.6 正规方程 

4.7 正规方程及不可逆性（选修） 

五、Octave教程(**Octave Tutorial**) 

5.1 基本操作 

5.2 移动数据 

5.3 计算数据 

5.4 绘图数据 

5.5 控制语句：**for**，**while**，**if**语句 

5.6 向量化 88

5.7 工作和提交的编程练习 

- [第三周](markdown/week3.md)

六、逻辑回归(**Logistic Regression**) 

6.1 分类问题 

6.2 假说表示 

6.3 判定边界 

6.4 代价函数 

6.5 简化的成本函数和梯度下降 

6.6 高级优化 

6.7 多类别分类：一对多 

七、正则化(**Regularization**) 

7.1 过拟合的问题 

7.2 代价函数 

7.3 正则化线性回归 

7.4 正则化的逻辑回归模型 

- [第四周](markdown/week4.md)

第八、神经网络：表述(**Neural Networks: Representation**) 

8.1 非线性假设 

8.2 神经元和大脑 

8.3 模型表示1 

8.4 模型表示2 

8.5 样本和直观理解1 

8.6 样本和直观理解II 

8.7 多类分类 

- [第五周](markdown/week5.md)

九、神经网络的学习(**Neural Networks: Learning**) 

9.1 代价函数 

9.2 反向传播算法 

9.3 反向传播算法的直观理解 

9.4 实现注意：展开参数 

9.5 梯度检验 

9.6 随机初始化 

9.7 综合起来 

9.8 自主驾驶 

- [第六周](markdown/week6.md)

十、应用机器学习的建议(**Advice for Applying Machine Learning**) 

10.1 决定下一步做什么 

10.2 评估一个假设 

10.3 模型选择和交叉验证集 

10.4 诊断偏差和方差 

10.5 正则化和偏差/方差 

10.6 学习曲线 

10.7 决定下一步做什么 

十一、机器学习系统的设计(**Machine Learning System Design**) 

11.1 首先要做什么 

11.2 误差分析 

11.3 类偏斜的误差度量 

11.4 查准率和查全率之间的权衡 

11.5 机器学习的数据 

[第7周](markdown/week7.md)

十二、支持向量机(**Support Vector Machines**) 

12.1 优化目标 

12.2 大边界的直观理解 

12.3 数学背后的大边界分类（选修） 

12.4 核函数1 

12.5 核函数2 

12.6 使用支持向量机 

- [第八周](markdown/week8.md)

十三、聚类(**Clustering**) 

13.1 无监督学习：简介 

13.2 K-均值算法 

13.3 优化目标 

13.4 随机初始化

13.5 选择聚类数 

十四、降维(**Dimensionality Reduction**) 

14.1 动机一：数据压缩 

14.2 动机二：数据可视化 

14.3 主成分分析问题 

14.4 主成分分析算法 

14.5 选择主成分的数量 

14.6 重建的压缩表示 

14.7 主成分分析法的应用建议 

- [第九周](markdown/week9.md)

十五、异常检测(**Anomaly Detection**) 

15.1 问题的动机 

15.2 高斯分布 

15.3 算法 

15.4 开发和评价一个异常检测系统 

15.5 异常检测与监督学习对比 

15.6 选择特征 

15.7 多元高斯分布（选修） 

15.8 使用多元高斯分布进行异常检测（选修） 

十六、推荐系统(**Recommender Systems**) 

16.1 问题形式化 

16.2 基于内容的推荐系统 

16.3 协同过滤 

16.4 协同过滤算法 

16.5 向量化：低秩矩阵分解 

16.6 推行工作上的细节：均值归一化 

- [第十周](markdown/week10.md)

十七、大规模机器学习(**Large Scale Machine Learning**) 

17.1 大型数据集的学习 

17.2 随机梯度下降法 

17.3 小批量梯度下降 

17.4 随机梯度下降收敛 

17.5 在线学习 

17.6 映射化简和数据并行 

十八、应用实例：图片文字识别(**Application Example: Photo OCR**) 

18.1 问题描述和流程图

18.2 滑动窗口 

18.3 获取大量数据和人工数据 

18.4 上限分析：哪部分管道的接下去做 

十九、总结(**Conclusion**) 

19.1 总结和致谢 

------



**机器学习qq群：865189078（我们有8个群，加过一个就不需要加了）** 

