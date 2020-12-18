# DeepLearning-Weekly
Collecting the most interesting deep learning（CV） applications, papers, and code for everyone！Waiting for your star!

### 人脸领域：

**:person_with_pouting_face:  人脸识别**

:heavy_check_mark:  [Towards Universal Representation Learning for Deep Face Recognition（CVPR2020解读）](https://blog.csdn.net/XBB102910/article/details/109428657)

> 提出了一种通用学习框架，可处理给定训练数据中看不到的较大变化，而无需利用目标领域知识。

:heavy_check_mark: [Sub-center ArcFace: Boosting Face Recognition by Large-scale Noisy Web Faces（ECCV2020解读）](https://blog.csdn.net/XBB102910/article/details/109400771)

> 以前的方法容易受到大量噪声label训练数据的影响，这需要人工清洗这些数据。本文放宽了ArcFace类内的约束，提高了对标签噪声的鲁棒性。

:heavy_check_mark: [The Elements of End-to-end Deep Face Recognition: A Survey of Recent Advances](https://blog.csdn.net/XBB102910/article/details/109279782)

> 关于人脸识别的最新进展综述，从三个方面详细介绍了整个识别系统各个模块：人脸检测、人脸图像预处理、人脸表示。阐述每一块技术的最新进展，包括最新算法设计、评价标准、数据集、性能比较、存在的挑战和前景广阔的研究进展。



### 目标检测：



:heavy_check_mark: [大白话 Generalized Focal Loss](https://zhuanlan.zhihu.com/p/147691786)

:white_check_mark: [丢弃Transformer，FCN也可以实现E2E检测](https://zhuanlan.zhihu.com/p/332281368)

:white_check_mark: [入门mmdetection](https://zhuanlan.zhihu.com/p/82503146)

### 模型训练：

:helicopter: [PyTorch分布式训练简明教程](https://zhuanlan.zhihu.com/p/113694038)



### 开源项目：

:convenience_store: [CVPODS：面向多种计算机视觉任务的多功能代码库：分类，分割，检测，自监督学习，关键点和3D 等](https://github.com/Megvii-BaseDetection)

- **[Detectron2](https://github.com/facebookresearch/detectron2)**：FAIR出品，基于caffe2；

- **[maskrcnn-benchmark](https://link.zhihu.com/?target=https%3A//github.com/facebookresearch/maskrcnn-benchmark)**：FAIR出品，基于PyTorch，可以看成Detectron的PyTorch升级版；

- **[MMDetection](https://link.zhihu.com/?target=https%3A//github.com/open-mmlab/mmdetection/)**：商汤MMLab出品，基于PyTorch，Model zoo相当完备；

- **[SimpleDet](https://link.zhihu.com/?target=https%3A//github.com/TuSimple/simpledet)**：图森出品，基于MxNet；

- **[Tensorflow Object Detection](https://link.zhihu.com/?target=https%3A//github.com/tensorflow/models/tree/master/research/object_detection)**：Google出品，基于TensorFlow 1.x；

  > 由 知乎：[小小将](https://www.zhihu.com/people/xiaohuzc)整理

### 模型部署

:car: ​ [YOLO之外的另一选择，手机端97FPS的Anchor-Free目标检测模型NanoDet现已开源~](https://zhuanlan.zhihu.com/p/306530300)

> code : https://github.com/RangiLyu/nanodet



### 可视化和深度学习可解释性

:train2: [卷积网络的可视化与可解释性](https://zhuanlan.zhihu.com/p/36474488)

> 资源整合，包括博客，paper，代码等

:airplane: [Tricks of PyTorch](https://github.com/lartpang/PyTorchTricks#pytorch%E6%8F%90%E9%80%9F)



### 编程 & 安装教程

:fire: [Google C++ 编程风格指南](http://staff.ustc.edu.cn/~tongwh/CG_2019/materials/Google%20C++%20Style%20Guide.pdf)

> 知乎相关提问：https://www.zhihu.com/question/430318186

:dragon_face: [PyCharm 专业版破解教程](https://mp.weixin.qq.com/s?__biz=MzU4NTY4Mzg1Mw==&mid=2247499891&idx=2&sn=9d13e38140e77a4645ca5b1d868791a1&chksm=fd844691caf3cf87ac7b31d4d40f546b4036db660de8de25fa16e7d445f294c9b33953d7434b&scene=27#wechat_redirect)

> 使用PyCharm和SSH搭建远程TensorFlow开发环境
>
> https://cloud.tencent.com/developer/article/1116623
>
> [PyCharm图解教程](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650769640&idx=1&sn=78082aaa6288496763050ca447edd25f&chksm=871a4c96b06dc58011dcb6b49318ff5b53f8b3ddcbc7b02b04f8552686b7ac98ae0c59e49303&scene=21#wechat_redirect)

:monkey: [PyCharm 常用设置（主题、样式、字体、字号）](https://blog.csdn.net/weixin_34613450/article/details/91372791)

### 论文资源

:blue_heart:  https://www.arxivdaily.com/

> 作者：https://www.zhihu.com/people/arxivdaily （每日推送论文）

### 在线测试demo & 趣味应用

:hand: 计算机视觉算法的在线Demo http://mc.nankai.edu.cn/ （南开大学媒体计算实验室）

> 详细介绍：https://zhuanlan.zhihu.com/p/183154662

:raised_hand_with_fingers_splayed: [人脸变形](https://medium.com/@azmariewang/face-morphing-a-step-by-step-tutorial-with-code-75a663cdc666)

<img src="https://github.com/Azmarie/Face-Morphing/raw/master/results/final-club-final.gif" width="300">

> github：https://github.com/Azmarie/Face-Morphing
>
> 三角剖分实现瘦脸/胖脸

:haircut_man: [Hairstyle Transfer](https://medium.com/swlh/hairstyle-transfer-semantic-editing-gan-latent-code-b3a6ccf91e82) 

> github: https://github.com/Azmarie/Hairstyle-Transfer

<img src="https://miro.medium.com/max/600/1*mVWxFMlgQEUX9ybyFvyGUA.gif" width=200>



### 基础积累

:joy:  [玩转pytorch中的torchvision.transforms](http://noahsnail.com/2020/06/12/2020-06-12-%E7%8E%A9%E8%BD%ACpytorch%E4%B8%AD%E7%9A%84torchvision.transforms/)



说明：

:heavy_check_mark: ：代表偏理论

:white_check_mark: ：代表偏实战