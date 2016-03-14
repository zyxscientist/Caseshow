#Caseshow
![desktop](http://7xrjhy.com1.z0.glb.clouddn.com/desktopdemo.png)

Caseshow是基于大神[Ruipeng Zhang](https://github.com/ppoffice)为Hexo开发的一套响应式模板开发的[minos](https://github.com/ppoffice/hexo-theme-minos)而重新设计的，或许你会发现，我并不是Fork过来的，而是自己删掉了origin重新commit到自己的repository里面。没错，一个月前的我还不会用Github，所以在我发现了这个简洁优雅的主题之后直接就下载了下来，然后非常开心地打开<!--more-->sublime就改了起来，等到minos以及被改成Caseshow这个样子之后一切看起来都迟了，谨以此文说明一下以及道声歉，这都因为我的无知造成的。

---
### 入正题吧~
寒假接触了Hexo，简直就是发现一片新大陆，配合github，每个人都可以免费拥有一个自己的专页（或者说博客吧），真是想想就有点让人感觉到激动呢。或许爱折腾hexo的都是前端和各类程序员们，我没有发现哪个主题是我真的喜欢的。虽然hexo这个平台确实已经存在了许多看起来非常不错的主题，但是与我的心理模型总有差距，比如说我不喜欢它们总是纵向排列每一条post。哪里有压迫，哪里就有反抗，我庆幸自己是个点了前端技能的交互哈哈哈哈哈，于是乎fire up我的sublime自己就干了起来。（哈哈其实说到底就是手痒了想打代码）

##### 多了些什么呢？
1.让文章以卡片的方式在主页呈现，一行代码就能设定卡片的大小，非常方便。
2.为卡片添加了一些简单的阴影效果，喜欢吗？
3.添加了可爱的带彩色背景的tag。
4.改变了一些手机端页面的样式。
5.将一些国内不能访问或访问速度难以保证的库转为国内镜像，尽量优化访问速度。
6.让favicon在chrome上也能够正常地显示。
7.更多微小的样式更改，不一一详述。


#### 主题安装


``` 
$ git clone https://github.com/zyxscientist/Caseshow.git
```

#### 要求
Hexo 3.0+
Grunt 0.4+
一般直接安装都没有问题，如果出现问题请自行google。

#### 升级
```
cd themes/caseshow
git pull
```

#### 设置



```Header
logo_text: 
subtitle_text: 
menu:
  Home: /
  Archives: archives
  Categories: categories
  Tags: tags
  About: about

Content
excerpt_link: Read More
toc: false #  Whether to show the table of contents in articles
fancybox: true

Miscellaneous
google_analytics:
favicon: /favicon.ico
```

---


- logo_text: 设置首页logo text，同时也是自适应移动设备之后menubar上显示的文字。
- excerpt_link: 在文章中插入<!-- more -->来让文章在首页仅显示你想要的到的长度。
- toc: table of content，你懂的。
- fancybox: 开启或者关闭fancybox功能。
- google_analytics: 请输入您的google analytics ID。
- favicon: 将格式为.ico的favicon放置到caseshow文件夹下即可正常显示，推荐使用32\* 32大小。


#### 界面
卡片式呈现你的post。

![desktop](http://7xrjhy.com1.z0.glb.clouddn.com/desktopdemo.png)


#### 响应式界面
Caseshow保留minos的自适应功能。

![mobile](http://7xrjhy.com1.z0.glb.clouddn.com/demomobile.png)


---
#### 好了，最后，感谢你使用Caseshow。
#### 如果觉得不错，可以star一下吗哈哈？







