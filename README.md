


> Written with [StackEdit](https://stackedit.io/).
机器学习纳米学位毕业项目
====
# 基于深度学习的猫狗识别
    本项目将训练一个可以从照片中识别出图片中的动物是猫还是狗的深度学习模型。
## 一、所需软件
* win 10 专业版
操作软件
* Anaconda2
Python环境及相关依赖包
* vs2015 
提供C++编译器
* CUDA 8.0 
并行计算架构
* CuDNN
专门针对Deep Learning框架设计的一套GPU计算加速方案
## 二、所需库
* mingw 4.7
可自由使用和自由发布的Windows特定头文件和使用GNU工具集导入库的集合
* libpython 2.0
* theano 0.8.2
基于Python的深度学习框架
* Keras 1.1.2
基于Theano的深度学习框架

## 三、硬件型号
* cpu
Intel(R) Core(TM) i7-3612QM CPU @ 2.10GHz 2.10GHz
* GPU
NVIDIA GeForce GT 640M

## 四、数据来源
本项目选择的数据集来自于kaggle上的dogs vs cat项目的train.zip
[训练数据集下载页面](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data)
[测试数据集下载页面](http://www.robots.ox.ac.uk/~vgg/data/pets/)

## 五、代码运行时间
python代码储存在dogs_vs_cats_170108.2.ipynb文件里
代码分为5个部分
#### 1.分析数据
运行时间 约10分钟
#### 2.图像预处理
运行时间 约20分钟
#### 3搭建卷积模型并进行初次训练
运行时间 约0.8小时
#### 4完善
运行时间 约2小时
#### 5模型评价及结果可视化
运行时间 约10分钟

