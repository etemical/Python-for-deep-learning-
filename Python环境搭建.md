## Python环境搭建

> 因为Python是跨平台的，它可以运行在Windows、Mac和各种Linux/Unix系统上。在Windows上写Python程序，放到Linux上也是能够运行的。(***此处介绍的环境搭建为AI深度学习生态的相关软件***)

 要开始学习Python编程，首先就得把Python安装到你的电脑里。安装后，你会得到Python解释器（就是负责运行Python程序的），一个命令行交互环境，还有一个简单的集成开发环境。

## 安装Anaconda

目前，Python有两个版本，一个是2.x版，一个是3.x版，这两个版本是不兼容的。由于3.x版越来越普及，我们的教程将以最新的Python 3.版本为基础。请确保你的电脑上安装的Python版本是最新的3.8.x，这样，你才能无痛学习这个教程。安装的方式又很多种，这里为了接下来的深度学习，我们推荐大家通过Anaconda来安装。
这个Anaconda是个什么玩意儿呢，可能刚开始很多同学很晕，他跟pythony有什么关系？别急，我们慢慢解释
还记得我们说过运行python程序需要解释器( *python是解释性语言，边解释边执行，没解释器，再好的py文件也无法执行* )
![python.exe ](https://upload-images.jianshu.io/upload_images/18298870-5e3263e9d4ce618e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**上图中的python.exe 就是python解释器**
但是我们做深度学习还需要很多其他的第三方包，比如numpy、matplotlib、pytorch、PIL等等，而Anaconda就是这么一个集成的python包管理和环境管理软件，里面为我们安装好了深度学习所需要的大量第三方包，所以我们直接安装它就好啦~~

>Anaconda的官网  [https://www.anaconda.com/](https://www.anaconda.com/)

除此之外，深度学习，包括python开发需要的相关软件如下：
* Anaconda
* Pycharm
* CUDA和CUDNN( *可能会需要visual studio2017，也可以不装*)
* Pytorch

#### 详细安装教程请参见我们发布的视频