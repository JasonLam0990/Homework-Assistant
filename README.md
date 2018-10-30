# Homework-Assistant
学委作业助手，你的学习好帮手

### 学委作业助手小程序码（长按扫描小程序码查看示例）
<center>
 <img src="/images/xwzs.jpg" margin=20% width=30% />
</center>

### 主要功能页面展示

<div style="display:flex;justify-content:space-around;"> 

 <img src="/images/bg.png" margin=20% width=30% />
 <img src="/images/myclass.png" margin=20% width=30% />
 <img src="/images/myhomework.jpg" margin=20% width=30% />
 
</div>

<div style="display:flex;justify-content:space-around;"> 
 
 <img src="/images/workdetails.jpg" margin=20% width=30% />
 <img src="/images/announce.png" margin=20% width=30% />
 <img src="/images/set.png" margin=20% width=30% />
 
</div>

<br>

<div style="display:flex;justify-content:space-around;"> 
 
 <img src="/images/setmanager.jpg" margin=20% width=30% />
 <img src="/images/managerclass.jpg" margin=20% width=30% />
 
</div>

#### 2018年8月23日 星期四

1.设计项目的UI布局<br>
2.基本完成项目的UI<br>
3.完善了分享以后的跳转以及传值逻辑<br>
4.完善各表单页面的post逻辑<br>

#### 2018年8月24日 星期五

1.UI界面完成，逻辑部分还未与服务端结合<br>

**近期感悟：感觉不能同一时间同时搞好几个项目，会容易感到迷茫和困惑，进而感到烦躁，降低coding效率。分清事情的轻重缓急以及重要程度，再去动手。所以学委助手这边我准备先放一放，但是会在开学第一周前做完上线！！**


#### 2018年9月22日 星期六 V1

1.因为比较忙，进度好像有、慢，现在正式版本终于上线了哈哈，希望能真正的帮到学委们<br>

#### 2018年9月26日 星期三 V1.1

1.增加了删除已发布作业的功能<br>

#### 2018年10月2日 星期二 V1.2

1.增加 删除创建的班级，退出加入的班级 的功能<br>
2.一些界面按钮的调整<br>
3.增加了作业、公告复制按钮<br>
4.增加了公告的删除功能，修复了“修改公告时候显示的不是当前公告，而是第一次发的公告”的bug<br>

#### 2018年10月5日 星期五 V1.3

1.增加了班级管理员的模块，管理员可以进行除了删除班级和授权管理员之外的其他功能。<br>
2.将updateUser的接口放到了index.js，之前放在app.js会保存不到用户的数据<br>

#### 2018年10月9日 星期二 V1.35

1.修复了用户点击微信群链接进去班级时，没有授权微信名和头像的问题，导致学委在查看管理员时出现null的情况。<br>
2.修复了iphone 7 plus设备上的一些显示错位的bug（myfile部分的微信名 && myclass中删除创建的班级时的弹出框）<br>
3.将workdetails中的内容和备注部分由 ```<view> </view>``` 改为 ```<text> </text>``` 这样子的话，用户在输入时的换行会被保留，更美观<br>

#### 2018年10月12日 星期五 V1.4

1.发布、删除、修改作业和公告或者退出、删除班级的时候不会都统一跳转到主页，而是会相应的在本页面重新加载新数据或者返回上一级页面。<br>
2.增加了功能介绍的部分，也就是在用户第一次创建班级，并进入该班级时，会有一个对功能按钮的高亮介绍。【通过本地缓存实现，如果第一次创建班级并进入时就会设置一个flag为false，此后为true的话就都不会再显示】)<br>

#### 2018年10月15日 星期一 V1.45

1.增加了设置的按钮，放在界面的右侧下方，点击设置按钮，可以选择是否隐藏已结束的作业以及引导用户关注服务号，一边获得新作业提醒。<br>
2.增加了“几天后”、“星期几”的时间标签🏷️，提升用户使用体验。<br>

#### 2018年10月30日 星期二 V1.5
1.增加了修改班级名称的功能，并对界面有一定的改动。<br>
2.设置管理员的界面为开启了服务号消息提醒的用户增加了一个标识。<br>
