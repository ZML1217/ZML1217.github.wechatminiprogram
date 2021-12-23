基于微信小程序开发的在线答题系统

 

摘要：随着时代的发展，大学生的时间越来越匆忙。很多时候无法抽出大量时间去集中学习，如今的碎片化时间越来越多，若不加以利用，大学生的时间将会被浪费很多。为了充分利用大学生的时间，且可以将这些时间花费到学习上，为此我们小组根据该构思设计了一款答题的微信小程序，里面设计了五套题目，题库可以不断地扩充，方便大学生在碎片化的时间中也可以学习。

 

关键词：碎片化时间；答题；微信小程序；大学生



​                                                                                **目录**

[1	项目概况	](#_Toc81386365)

[1.1	总体思路	](#_Toc81386366)

[1.2	需求分析	](#_Toc81386367)

[1.3	概要设计	](#_Toc81386368)

[2	软件设计	](#_Toc81386369)

[2.1	设计说明	](#_Toc81386370)

[2.2	模块说明	](#_Toc81386371)

[3	实现结果	](#_Toc81386372)

[3.1	测试环境	](#_Toc81386373)

[3.2	运行条件	](#_Toc81386374)

[3.3	成果展示	](#_Toc81386375)

[4	参考文献	](#_Toc81386376)

 

# **1**  项目概况

## **1.1**  总体思路

该项目受众对象是大学生，对于大部分大学生来说，他们的碎片化时间非常多，碎片化时间就是指很多零用的时间。碎片化时间由于小而多，无法充分利用，我们开发此小程序的目的就是帮助大学生充分利用碎片化时间进行学习，节省出更多的时间解决其它事情，不需要额外花更多的大块时间去解决这些问题，形成良性循环。

## **1.2**  需求分析

实际问题：该项目含有较多套试题，试题可以在数据集中丰富起来，以适用于各个专业的大学生。试题中含有单项选择题和多项选择题等，学生们在碎片化时间中可以完成不少题目进行学习，强化知识点记忆。学生们可以记录笔记以便之后可以想起自己做了什么。学生们可以收藏和评论题目，也可以对答案提出质疑，其它用户可以解答或者联系我们进行解答。

***\*功能需求：\****学生们的主要功能需求是答题、题库、成绩、收藏和评论等功能，这也是我们开发的核心内容。

## **1.3**  概要设计

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21C6.tmp.jpg) 

​                                           1-1 微信小程序开发

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21C7.tmp.jpg) 

​                                       1-2 微信小程序-答题-功能

# **2**  软件设计

## **2.1**  设计说明

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21D7.tmp.jpg) 

​                                                       2-1 代码模块

 

## **2.2**  模块说明

### 2.2.1 page文件夹

该文件夹用于存放各种页面，如home、logs、mine和test等页面，用于方便管理各个页面，以及页面之间的联系、跳转等。每个页面包含四个文件，分别是.js、.json、.wxml和wxss,.js的作用是给页面添加动作逻辑，让页面可以动态起来，执行动态命令；.json的作用是给标题头命名等；.wxml的作用是给页面添加内容；.wxss的作用则是改变页面的样式，包括颜色、排版和大小等。

文件夹下面的页面：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21D8.tmp.jpg) 

页面下的四个文件：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21D9.tmp.jpg) 

 

### 2.2.2 image文件夹

image文件夹里面含有涉及到各个页面含有的图片，包括各种图片，放在该文件夹下方便管理，这是其中的一种存储图片的方法，在页面中也可以使用图片链接来代表图片。

展示部分图片：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21DA.tmp.jpg) 

 

### 2.2.3 data文件夹

该文件夹下面存放着.json格式的数据集，该数据集也可以拆分建立起一个数据库，利用云开发与前端进行交互，传送数据。

data文件夹：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21DB.tmp.jpg) 

json文件内容部分展示：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21DC.tmp.jpg) 

# 3  实现结果

## **3.1**  测试环境

硬件配置：W	indows，英伟达MX250，8.00GB

操作系统：Windows/x64位操作系统

开发语言：javascript/1.8

开发工具：微信开发者工具/1.05

## **3.2**  运行条件

### 3.2.1 百度搜索微信公众平台

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21DD.tmp.png) 

### 3.2.2 找到微信小程序开发工具的下载页面

https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html,选择对应的windows版本

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21DE.tmp.png) 

### 3.2.3 下载完成后运行安装程序,安装程序为.exe格式.双击可运行,下一步

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21EF.tmp.png) 

这一页是许可协议，同意,我接受

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21F0.tmp.png) 

在这一步选择要安装的位置

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21F1.tmp.png) 

前边的设置完成后,在这一步就开始释放文件进行安装了，耐心等待

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21F2.tmp.png) 

安装完成后,就会给出安装完成的提示信息

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21F3.tmp.png) 

### 3.2.4 选择运行就会出现开发工具的界面

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21F4.tmp.png) 

在这里需要使用微信扫一扫才能正常使用

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps21F5.tmp.png) 

## **3.3**  成果展示

### 3.3.1  首页

答题小程序分了两个模块，“答题”和“我的”。

“答题”：

该界面含有五套试题，用户可以根据需求选择自己所需要的试题。

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps2206.tmp.jpg) 

 

### 3.3.2  试题 

#### 3.3.2.1  选取试题1

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps2207.tmp.jpg) 

这是刚进去的界面，为多选题，用户需要选择答案进入下一题，如不想答题，可点击右下角退出答题。

#### 3.3.2.2  退出答题界面：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps2208.tmp.jpg) 

 

以此类推，共计十道题目，回答完之后会提示得分以及答错的题目：

#### 3.3.2.3  得分界面：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps2209.tmp.jpg) 

#### 3.3.2.4  查看错题界面：

该界面会显示自己的答案和正确答案，

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps220A.tmp.jpg) 

看完之后可以选择再来一次和返回首页。

以此类推，共计五套试题，操作同上。

 

### 3.3.3  “我的”

“我的”界面：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps220B.tmp.jpg) 

分了五个模块，“获取头像昵称”、“我的成绩”、“我的收藏”、“我的评论”和“我的设置”。

 

#### 3.3.3.1  获取头像昵称：

可以实时获取用户的头像和昵称，实图如下：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps220C.tmp.jpg) 

 

#### 3.3.3.2  我的成绩：

我的成绩模块记录了每一次的答题记录，含时间、试题名字和得分，点击该模块即可跳转，实图如下：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps221C.tmp.jpg) 

#### 3.3.3.3  我的收藏

在该界面中可以存放用户收藏的试题，并将数据返回数据库，专门存放收藏的试题，取消收藏试题之后，该界面也将不展示该试题，并反馈给数据库，让数据库删除收藏试题。

实图如下：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps221D.tmp.png) 

 

#### 3.3.3.4  我的评论

该界面主要是为了存放他人的评论，如对试题的评价，或者是对答案正确与否的反馈。评论内容可产生较大的数据量以及访问量。

 

#### 3.3.3.5  我的设置

该页面中有密码修改；手机修改，即修改手机号；下一个就是关于我们，可以通过这个联系开发者，可以询问问题或者提供一些改进建议；最后一个就是清除缓存，就是清除一些占用内容但是可以通过网络重新加载回来的数据。

实图如下：

![img](file:///C:\Users\T-sing\AppData\Local\Temp\ksohtml\wps221E.tmp.png) 

 

### 3.3.4 心得体会

以上就是整体答题小程序的介绍，题目可以修改数据库或者添加，在data.js文件可以完成修改。基础功能完善，核心答题功能已实现。和小组共同开发该小程序，我的组织协调能力增强了，并且可以独立开发微信小程序了，前端+云开发会比使用java等做的后端使用方便些。

我们项目成员共有三个人，分别是19060517121邹闽路（负责人），19060517120朱恒延，19060518104樊鑫，分工合作，邹闽路负责前端页面和后端系统架构设计并完成部分核心代码，朱恒延负责代码完善，页面添加，测试代码和功能小程序等工作，樊鑫则负责数据库设计以及数据收集修改等工作，并了解一定的前端页面和后端架构，方便连接工作。

该项目将数据库整合在了前端，当然，也可以将数据写回数据库，利用JAVA后端或者微信小程序提供的云开发平台进行交互，融合转换实现较容易，修改部分代码再连接数据库和后端即可。

在开发过程中，我发现云开发有非常多的便捷之处，你不需要自行连接后端和数据库，只需要在.js页面写交互代码即可，数据就可以在前后端相互传送，微信小程序也对应地给出了对应云开发平台。云开发也有缺陷，比如安全性，容易产生数据泄露等，不过在对于我们这种非上线的小项目来说，可以忽略这个问题，如果考虑上线，还是比较建议JAVA后端，毕竟JAVA也比较成熟了，云开发平台不过才发展了几年时间，目前还无法追赶上JAVA专门做后端的平台。

开发过程中参考了很多资料以及自学了较多东西，对自己产生了很大的帮助。开发过程中加强了思考能力以及创新能力，这些能力在参加互联网+比赛和大学生创新创业项目中有非常大的帮助，我也参加了较多的省级项目，从中吸取了很多经验，比如如何分配任务，如何开发并且执行下去，以及如何编写优秀的软件设计文档，在借鉴的同时，也加强了这些能力。

# **4** 参考文献

## 4.1 微信开发者文档			

https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html

## 4.2 Vant Weapp组件库

https://youzan.github.io/vant-weapp/#/home

## 4.3 GitHub代码托管平台

https://github.com/

## 4.4 Gitee代码托管平台

https://gitee.com/

## 4.5 微信小程序开发教程参考文档

https://blog.csdn.net/valada/article/details/80892569?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163833417616780357211679%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163833417616780357211679&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-2-80892569.first_rank_v2_pc_rank_v29&utm_term=%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%BC%80%E5%8F%91&spm=1018.2226.3001.4187

 

 

 