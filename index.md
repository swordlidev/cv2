# 李剑
<p align='center'>
  <img src='https://github.com/lijiannuist/lijiannuist.github.com/blob/master/images/lijian.jpg' width='240'/>
</p>

### 基本信息    
'''          
* 出生日期：1994/11/14                  
* 籍贯：江苏 盐城                
* 政治面貌：党员     
* 手机：147 5160 0355
* Email：lijiannuist@gmail.com;   1203807895@qq.com
* 主页:  [Resume](https://docs.google.com/document/d/1ddRU1buDke8axs8mxEqLi9sdZ4g2QyzMW3uAhkqwaV4/edit?usp=sharing),    [Github](https://github.com/lijiannuist),   [微博](https://weibo.com/3012693523/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1) , [知乎](https://www.zhihu.com/people/lijiannuist/activities)
'''
### 教育经历

*   2016.09-        南京理工大学      计算机科学与工程学院 导师：[杨健](https://baike.baidu.com/item/%E6%9D%A8%E5%81%A5/9376288?fr=aladdin), 钱建军, [PCALab](http://www.patternrecognition.cn/)
*   研究方向：目标检测，深度学习，计算机视觉，自动驾驶
*   2012.09-2016.06 南京信息工程大学  数学与统计学院  信息与计算科学 GPA: 88.35 TOP：4/71    
*   专业课程：数学分析、高等代数、概率论与数理统计、数据结构、数值分析

### 专业技能
* 	熟悉C/C++、Matlab、python、Jave、Mysql、Opencv、caffe、vtk、pytorch、ros、pandas。
* 	有较好的程序算法设计能力，较好的数学建模能力。
* 	英语CET-6（527），能进行日常简单交流，可熟练阅读英文资料。
*   三年以上计算视觉研究经历，有数据挖掘经验。

###  工作经历
* 2018.07-      人脸检测    [腾讯优图实验室人脸组](https://open.youtu.qq.com/#/open)    mentor：王亚彪  

    从事人脸检测方向的研究，主要探索one-stage检查器用于人脸检测，期间复现过S3FD，pyramidbox，refinedet，retinanet，FPN，Focalloss等前沿工作。基于SSD加入前沿的方法如：采用resnet101作为backbone，使用FPN对特征进一步加工，引入context信息，使用mio抑制背景类，使用head，body弱监督信息，更加丰富的数据采样方式，调节anchor的尺度等策略。提出的DSFD工作在WIDERFace人脸检测数据集上面的得分：easy：0.966，medium：0.957，hard：0.904.取得STOA，相关工作发表在2019CVPR上。

* 2017.10-2018.03  多标签图像分类  腾讯微信模式识别中心  mentor：李岩  

    此项目是[腾讯犀牛鸟精英研究生计划](http://cs.njust.edu.cn/43/55/c1817a148309/page.htm)，基于微信朋友圈图像数据构建一个大规模多标签图像数据集，该过程涉及挖掘朋友圈数据的文本信息，根据词频选取5000个特色关键字例如“小黄车”作为标签，以此关键字搜索图片并通过kmeans聚类后进行图片清理，每个关键字选取1000张图片构建原始数据集。用该数据集基于pytorch训练一个resnet50多标签图像分类引擎。该模型可对微信公众号及朋友圈图像打上多个标签，该标签用于用户画像并进一步用于音乐推荐系统的特征构成。
 
* 2017.07-2017.09    车辆轨迹预测    图森    mentor：王乃岩 

    在该自动驾驶初创公司实习期间，主要研究对自动驾驶车辆的周边行车进行轨迹预测以此来避免碰撞。主要基于点云数据估算后的位置信息，使用了kalman filter来对周边车辆进行轨迹跟踪, 同时也探索用xgboost , lstm 等技术对下一个时刻的车辆位置进行估计。同时建立预测的评价指标评估预测结果。

* 2016.06-2016.09    基于深度学习的目标检测    虹软    mentor：林建华 

    在虹软实习期间，学习主流深度学习检测算法（FasterRcnn，YOLO，SSD），借鉴SqueezeNet修改SSD网络的backbone，以此提高检测速度，减少模型参数。同时将caffe训练出来的模型解析出参数，用纯C++写的前向网络进行部署，提供基于手机端的SDK。
     
###  在校项目

* 2016.1-2016.6    中文手写字体检测与识别    北京大学    计算机研究所    字形计算实验室    导师：连宙辉

    本人于2015.7月参加北京大学计算所夏令营，通过北大推免预选拔。 9月本校推免失败，故于2016.1月起在北大计算所实习。实习内容涉及手写汉字二值化、分割、以及 OCR，使用opencv、深度学习框架 caffe 开发，基于CASIA库训练的alexnet_model可参考：[HCCR](http://pan.baidu.com/s/1qYCbfqs)。

* 2014-2015    医学图像分割    南京信息工程大学    数学统计学院    图像处理实验室    导师：陈允杰 

    该项目是本人在数统院图像处理实验室完成。主要研究了基于统计的图像分割算法（K-means、FCM、GMM），并提出将非局部信息融入现有的模型当中，提出一种新的FCM方法：Non-local-based spatially constrained hierarchical fuzzy C-means（SCI）。同时，独立开发一套基于vtk的脑核磁共振图像三维分割系统。

* 2013-2015    自动指纹识别    南京信息工程大学    计算机学院    指纹组    导师：梅园

    该指纹组由四位本科生组成，由计算机学院老师带队，本人负责指纹方向场的建模和计算（PDE、DCT等），提出一种基于改进的偏微分模型的指纹方向场计算方法并申请获得专利，同时对现有的算法进行改进，提出一种谱方法计算指纹方向场。除此以外，也曾研究以指纹方向场作为指纹特征对其进行分类。指纹组也开发出一套基于C++的自动指纹识别系统。在该系统中，本人负责实现指纹方向场的代码。

### 竞赛经历
* 2018.12    [AIChallenger无人驾驶视觉感知赛](https://challenger.ai/competition/adp2018)    亚军    奖金4万人民币

    本次大赛赛题是无人驾驶视觉感知，共有两个任务分别是道路中的物体检测和道路分割，比赛数据使用的是BDD100K，在检测任务中我们使用了cascade、Multi-head Ensemble方式优化模型，在分割任务中使用Res50+PSPNet作为基准模型进一步优化模型速度。在决赛C榜上，我们的成绩是检测mAP23.7，分割mIOU77.5，模型的FPS为16.0，其中检测任务的融合模型在BDD100K数据验证集上取得36.6的最高分。最终Amadeus队伍获得亚军。[官方获奖名单](https://challenger.ai/news/ai_challenger_2018_winners) 
    
* 2017.09    [Didi-Udacity无人驾驶挑战赛](http://research.xiaojukeji.com/)    冠军    奖金10万美金

    本次大赛赛题是无人驾驶，要求参赛者找到通过摄像头和 LIDAR 数据检测道路上的障碍物的最好方法。要求参赛者实时处理 LIDAR、RADAR及摄像头原始数据，输出障碍物位置、移除噪音和环境错误检测。最终的代码方案需要基于ROS 架构（Ubuntu 14.04, ROS  Indigo）、并能够在搭载 I7 和 Titan  X的 平台上以至少 10Hz 运行。我们提出了一种基于多传感器由粗到细的障碍物检测框架（multi-sensor coarse-to-fine detection  framework）。在该框架中，对于相机图像，采用深度学习算法（YOLO），对于点云数据，采用精心设计的聚类和识别算法。该框架能在达到最高的检测指标（IOU）的同时也能够有很快的检测速度，最终我们的成绩在两轮leadboard上都排名第一，现场真车测试速度达到20FPS。[学院新闻报道](http://cs.njust.edu.cn/49/27/c1817a149799/page.htm) , [新浪教育](http://edu.sina.com.cn/l/2017-09-22/doc-ifymfcih2432055.shtml), [知乎专栏](https://zhuanlan.zhihu.com/p/29907537)

* 2017.01    [Ucar-Bitiger深度学习无人驾驶挑战赛](https://www.bittiger.io/competition?utm_source=Zhihu&utm_medium=Lurenjia&utm_content=post733)    冠军    奖金5000美金 

    本次大赛的任务是利用神州专车北美实验室提供的10000张标注好的训练图像数据，运用深度学习模型检测出给定图像中的车辆、行人、交通标志等物体的Bounding Box并识别。本次大赛包含两个赛季，其中初赛和复赛需要选手线上提交2000张和3000张图像的检测结果。 我们通过改进R-FCN 以及集成更多的特征提取网络来提升我们的检测性能，同时采用multi-scale train和test策略，最终获得冠军。[学院新闻报道](http://cs.njust.edu.cn/1b/66/c1817a138086/page.htm) [中国科学网报道](http://science.china.com.cn/2017-02/09/content_9327659.htm)

* 2016.11    上海BOT大数据竞赛视觉组    亚军    奖金5万人民币    

    本次该比赛分三个赛季，包含三个任务，分别为：（1）12种动物识别，（2）货架商品检测，（3）视觉问答。在货架商品检测任务中，面对种类繁多且稠密的小目标问题时，我们引入反卷积修改SSD网络以增加图像分辨率，同时由于图像标志较少只有几百张，我们对图像进行裁剪拼接以增广数据. [学院新闻报道](http://cs.njust.edu.cn/08/81/c1817a133249/page.htm)

### 个人荣誉
*   2018.07    工信部创新创业二等奖学金；
*   2017.11    南京理工大学校长奖章（学校最高荣誉）；
*   2017.10    研究生国家奖学金，校一等奖学金；
*   2016.09    全国研究生数学建模国家二等奖；
* 	2015.03    美国大学数学建模国家二等奖；
* 	2014.11    “高教社杯”全国大学生数学建模大赛国家二等奖；
* 	2014.05    “蓝桥杯”程序设计大赛国家二等奖、江苏省一等奖；
* 	2014.07    “中国计算机设计大赛”国家三等奖；
* 	2015.05    江苏省三好学生；
* 	2012-2015  南京信息工程大学校三好学生、校优秀共青团员、校优秀学干、校学生会优秀部长；

### 发表著作
*    Li Jian, Wang Yabiao, Wang Changan, Tai Ying, Qian Jianjun, Yang Jian, et al. "DSFD: Dual Shot Face Detector." IEEE Computer vision and pattern recognition (CVPR), 2019.  
*    Li Jian, Qian Jianjun, and Yang Jian. "Object detection via feature fusion based single network." IEEE International Conference on Image Processing (ICIP).2017.
*    Li Jian, Qian Jianjun, and Zheng Yuhui. "Ensemble R-FCN for Object Detection." Advances in Computer Science and Ubiquitous Computing. Springer, Singapore, 2017. 400-406.
*    Li Dejian, Li Jian, Nie B, et al. "Deconvolution single shot multibox detector for supermarket commodity detection and classification[C]." Ninth International Conference on Digital Image Processing (ICDIP). 2017, 10420: 104202R.
*    Chen Yunjie, Li Jian et al. "Non-local-based spatially constrained hierarchical fuzzy C-means method for brain magnetic resonance imaging segmentation." IET Image Processing 10.11 (2016 SCI): 865-876.
*    一种基于改进的偏微分模型的指纹方向场计算方法 CN201510102734.5 梅园，李剑；
*    一种鲁棒的工业电表数字识别方法 CN201611031147.2 李剑，钱建军，杨健；

