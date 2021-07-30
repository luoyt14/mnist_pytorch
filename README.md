# 使用Pytorch的示例程序

1. 在此给出使用pytorch用于手写数字识别(mnist)的示例程序，方便大家修改修改用于大作业中；

2. 助教调试使用的环境为：pytorch 1.1.0+torchvision 0.3.0+cuda 9.0，在测试集上准确率约为98.3%，使用新版本应该也是可以的，如果有问题可以咨询助教答疑

3. 程序中提供了比较清晰的注释，大家可以参考，在此列出几个pytorch的教程和参考文献，供大家学习

> * Pytorch的中文文档，可以查看相应函数的参数含义，例如nn.Conv2d等： https://pytorch-cn.readthedocs.io/zh/latest/
> * Pytorch自定义数据集，方便大家将大作业提供的数据载入到pytorch中，https://pytorch.apachecn.org/docs/1.4/5.html，https://www.jianshu.com/p/2d9927a70594
> * Pytorch定义神经网络结构，方便大家设计较好的网络结构来提升识别准确率：https://zhuanlan.zhihu.com/p/80308275，另外大家也可在github上多看看别人的网络结构定义
> * 最最重要的参考网址：pytorch的官网(https://pytorch.org/)，可以查看最新版本pytorch中各个函数的参数含义以及使用方法，不过是英文的

4. 在此给出pytorch CPU版的安装方式，GPU版大家可参考官网(https://pytorch.org/)

   1. windows安装：首先按照之前的python安装教程安装好anaconda，并且设置为清华源，然后打开Anaconda Prompt，输入如下命令：

      `conda install pytorch torchvision torchaudio cpuonly -c pytorch`

   2. mac安装：同样按照之前的python安装教程安装好anaconda，并且设置为清华源，然后打开终端，输入如下命令：
   
      `conda install pytorch torchvision torchaudio -c pytorch`

