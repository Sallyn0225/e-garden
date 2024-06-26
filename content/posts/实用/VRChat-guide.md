---
title: 怎样提高VRChat的游玩体验
date: 2023-12-27 19:55:47
tags:
  - 游戏
  - VRChat
categories:
  - 实用
keywords:
  - VRChat
  - 教程
  - 入门
  - 新手
  - 教学
description: 
share: true
cover:
  image: https://s2.loli.net/2024/04/13/kWHjrx3SzuVRmag.webp
dir: posts/实用
---

# 引言

临近23年年末，突然发现自己的VRChat游玩已经过去了一年的时间。

~~虽说今年下半年几乎一直在打CS2~~，但是自己的VRChat游戏时长也有接近1600小时了。说多不多，说少不少。刚好年末，把自己之前游玩的一个流程记录一下。所谓`create, share, play`是VRChat的slogen，那么现在该回到**share和create**的环节了

![游戏时长](https://pic.imgdb.cn/item/658cdd82c458853aef8d5c86.jpg)

我想从大概两个部分开始说起，一个是**游戏内部的一些设置**，有的可以提升你的游戏体验，有的则是藏的比较深的功能开关。另一个是**第三方的软件**，可以让你游玩时候的体验能够更上一层楼

---

## 游戏内设置

### 优化性能

#### 设置一个好的shield

说shield，其实也没那么高大上。本质上就是官方几个安全等级再加上一个可以自定义设置的custom等级罢了。为什么这个地方最好还是手动设置一下呢？因为哪怕是最高等级的紫名，如果你和我一样喜欢没事往一下老外比较多的图里跑的话~~请不要把某神社和某黑猫相提并论~~，碰到紫名一堆堆的概率可算是太多太多了。自然最高的等级也没有什么用了。

那么我是怎么优化的呢？首先我们要明确一下优化的目的。我的目的首要是不卡就行，看模型适应其次。那么，我有几个要求。

- 好友的模型始终加载，但是**看不到的距离外不加载**
- 所有陌生人的模型均不加载，感兴趣了再手动打开
- 手动打开的陌生人模型在**距离远了也不加载**

有了这些，那我们设置思路就很明确了。按照下图这么设置。

首先，我们直接来到custom的预设，把除了好友以外的部分都只给一个1、3权限 *（即语音、头像和表情。我用的是测试版所以会有中文）*

![除好友以外的等级](https://pic.imgdb.cn/item/658cdeabc458853aef918740.jpg)

然后，我们给好友进行如下的设置，除了**粒子和光照和模型动画**可以都打开。`如果你看到有的好友模型有问题，那么请你手动选中它按小眼睛进行一个全部的打开。毕竟我想没有人的模型会不用到粒子效果`

![custom截图](https://pic.imgdb.cn/item/658cde1ac458853aef8f5c7b.jpg)

接下来我们来进行一个距离的设置。

![模型距离和下载设置](https://pic.imgdb.cn/item/658ce06fc458853aef97122c.jpg)

如图，**距离和数量**你可以根据自己电脑的性能以及地图的大小进行一个设置。*比如神社这种大图就可以把距离稍微拉大一点* 

而我关闭了好友已经手动打开的模型的始终显示则是为了实现距离远了好友模型则不显示的功能。同时好友的模型将会优于手动打开的用户的模型进行下载。

#### 更改一下渲染质量

1. 把画质调到最低
    
    VRChat可不像别的游戏，你根本就不需要对设置里的那几个画质选项进行过多的思考——因为说实话，~~看着都一样~~，说不定你带上VR之后卡顿还更明显呢？
    
    ![最低的画质设置](https://pic.imgdb.cn/item/658ce149c458853aef9972cb.jpg)
    
    这里下面有个**限制粒子，请打开**
    
    以及一个像素光照数量，实测调到**关闭**都可以
2. 抗锯齿
    
    希望你没有把这个东西开的太高，因为这玩意是真得很卡！！但是它确实对画质得影响比较大，这里就看个人吧。低配的可以选择低一点。
	
	![抗锯齿设置](https://pic.imgdb.cn/item/658ce2a9c458853aef9dcbd7.jpg)
	
	**补充：这个东西你其实可以直接禁用，因为实测观感也大差不差**

### 默认关闭的开关

其实VRChat本身还有很多很实用的功夫默认术没有启用的状态，下面将会简单介绍一下可以启用的部分功能。

#### 名牌展示状态文字

这个功能启用主要是曾经逛街的时候发现有的人的状态是他们的discord ID，或者别的一些比较整蛊的文案，~~也可能你在向人家搭话之前可以发现人家状态上写了在和npy一块呢~~ 

![名字栏显示状态](https://pic.imgdb.cn/item/658ce3a8c458853aefa0b528.jpg)

开启的方法也很简单，按出轮盘菜单，依次`选项-名牌-状态-始终显示`即可

![开启方式](https://pic.imgdb.cn/item/658ce341c458853aef9f8fa7.jpg)

#### 小菜单的侧边栏

这个东西默认是收起的状态，你可以按这里的三条杠把它展开，然后选择你会用到的常用功能进行一个快捷的查看。比如我这里就放了一个快速修改我当前状态和模型的侧边栏。

![侧边栏设置](https://pic.imgdb.cn/item/658ce4aec458853aefa3c2ae.jpg)

#### 面部镜子

搓表情经常会用到的功能。

![面部镜子效果](https://pic.imgdb.cn/item/658ce4ffc458853aefa4c214.jpg)

打开也很简单，打开轮盘菜单。依次选择`选项-个人镜子-设置-表情镜`，打开并进行对应的设置就可以了。

![面部镜子设置](https://pic.imgdb.cn/item/658ce55fc458853aefa614c5.jpg)

## 第三方软件

### VRCX

[VRCX的github页面](https://github.com/vrcx-team/VRCX)

终于到了我最喜欢的部分，有了这个东西，你可以很方便的把游戏以及官方的[VRChat Home](https://vrchat.com/home)的网页版的功能进行整合并且一步到位的使用。

以下是部分VRCX可以做到但不限于的功能，同时也是我最常用到的功能。

#### 记录好友动态

==**本功能有可能会引起反感，请谨慎使用。**==

VRCX本身利用了VRC官方的API，所以它可以记录但不限于你的**好友状态/名字/地点**的变更。并且你可以通过点击查看详情。比如我看到我的一个好友加入了某一个地图的某一个房间内。只要这个信息在网页版能够看得到，那么VRCX就是可以记录下来的。

![VRCX-记录好友动态](https://pic.imgdb.cn/item/658ce7d7c458853aefaf1803.jpg)

同时你也可以看到这里是有搜索框的，输入相关信息`如好友名字，地点`都是可以进行查询的

#### 游戏动态记录

这个标题似乎有些抽象了。其实用的最多的就是记录下哪些人加入/离开房间以及对应的时间，还有播放视频的记录（利用游戏内的播放器）。一般我用来找那些聊过天但是一时间没来得及加上好友的人

![VRCX-记录游戏动态](https://pic.imgdb.cn/item/658ce898c458853aefb1c14a.jpg)

#### 批量管理你的收藏

有一说一，VRC的那个菜单界面，无论是搜索还是收藏，都让我用着有一种便秘的感觉。而VRCX很好解决了这一个痛点。你可以批量管理你收藏的世界或者模型，甚至可以导出列表。如果你的朋友也用这个软件，那么他可以选择导入。这对于分享游戏图或者风景图是非常方便的。

![VRCX-批量管理收藏](https://pic.imgdb.cn/item/658ce955c458853aefb3d4f7.jpg)

### Yukarinette Connector Neo

这是一个可以把你的话转换成别的语言并通过文本框显示在你头上的软件。官网我放在这里。

[Yukarinette Connector Neo 官网](https://nmori.github.io/yncneo-Docs/)

#### 设置过程

首先拿到软件先得设置一下语言

1. 点击插头按钮
2. 按齿轮按钮
3. 直接叉掉关闭，软件会自动重启

![YCN初始化](https://pic.imgdb.cn/item/658ceb52c458853aefb9bd6f.jpg)

然后我们重新启动，点击左边的侧边栏，依次设置。
1. 把**自己说的语言**填进去，这里我填中文。
2. 识别系统选择**浏览器**
3. 选择你想翻译出来的语言，如果有API可以不用共同服务器，一般懒的话**直接用共同就行**
4. 回到小插头图标，搜索输入`VRC`应该就可以跳出相应的插件了，安装即可

![](https://pic.imgdb.cn/item/658ced0fc458853aefbec4ac.jpg)

然后我们需要对启动的这个VRC插件进行一些设置
1. 填写你的主机名，端口默认9000/9001即可，不用更改
2. Address 一般默认`127.0.0.1`即可，我这个有点问题所以手动获取了一下本机的IP，你如果`127.0.0.1`可以用的话就不用进行更改
3. 把母语和刚才设置的翻译语言进行打勾，想翻译什么就勾你刚才设置的那个。
4. 切换到`VNC Msg`页面，全选即可

![YCN-插件页面设置](https://pic.imgdb.cn/item/658ceeb2c458853aefc386d4.jpg)

现在点击上方栏的麦克风按钮，按start就会自动开始识别了。如果头上没有蹦文字，检查你是否打开了VRC的**OSC功能**，轮盘菜单中`选项-OSC`就可以启用了。

![YNC效果预览](https://pic.imgdb.cn/item/658cef5ac458853aefc5ee4b.jpg)

# 结尾

以上就是本文的全部内容了。其实本质不算一个全面的优化设置或者软件推荐。不过设置和软件都是大部分人没有了解到的。希望本文的内容能够有所帮助。