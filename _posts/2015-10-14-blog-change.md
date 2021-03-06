---
layout: post
title: 博客改版记
tags: geek
excerpt_separator: <!--more-->
comments: true
sticky: false
hidden: false
toc: true
---

## 前言

萌生出搭建一个自己的blog，应该是大二的时候。一方面是觉得自己去写一个Blog可以学习Web开发的知识，另一方面则是想要找寻一片自己的天地，我可以在其中尽情的书写。当然，那个时候自己太懒，也没有什么技术能力可言，对于后台开发根本是一无所知，所以，写一个Blog的梦想就一直搁浅着。后来，一个偶然的机会，在网络上看到Wordpress可以非常方便地建站。但是，稍微看了一下，发觉好像要配置环境，于是，就又懒得动手了（*写下这些记录是，才意识到自己是一个多么懒惰的人，而且动手能力奇差*）。<!--more-->

## WordPress建站

开始拥有自己的Blog, 其实是大三下学期的事了。当时刚从台湾回来，不知道怎么的，突然迫切地想要提升一下自己的"技术水平"。觉得是时候动手搞一下WordPress了。人生中很多事情，应该说是，*说时容易做时难*。然而，搭建WordPress这件事，恰恰相反，确实比想象中要容易得多。回头想想，WP其实就是像普通地安装软件那么简单而已。当时是真的认为能搞出一个网站是一种技术能力的证明。哎，往事不堪回首。     

当时的想法，是希望能够把这个博客纯粹做为自己的私人空间，所以，并没有找云平台去部署，只是使用XAML搭建在Ubuntu本地环境中。后来，看到**为知笔记**更合适这种记录的想法，加上看到舍友使用为知笔记来分类收藏资料（*使用网页截取工具*），觉得也是相当的不错。同时也由于对于WP的Blog的实现难度已经失去了神秘感，那个Blog也就从此疏于维护管理。最后，在某一次重装系统中，整个Blog就不了了之了。      


## 转向Jekyll

第一次和Jekyll结缘，是受到了[Maple](http://miao.hu)这个博客的简洁性的吸引。于是去了解其实现的平台，便开始认识了Jekyll这个静态网站。发现它可以部署到Github上，不用花费一分钱，所以，就开始使用它写Blog了。     

第一个Jekyll博客，用的就是Maple网站的Theme，然后自己略作修改。    


## 爱上侧边栏

不得不说，Maple的那个Theme确实是非常的简约，简约到后来开始觉得它太过单调。于是，在某个无聊的晚上，我开始在网上Search Jekyll的漂亮主题。最后，在知乎上[某一答案](http://www.zhihu.com/question/20223939/answer/29742210?utm_campaign=webshare&amp;utm_source=weibo&amp;utm_medium=zhihu)看到了[林安亚的博客](http://painterlin.com/),符合我的想法。而看上它的最大原因，就是那个侧边栏(sidebar)。     

于是，我就换用了这个新的主题。然而，它还是有很多细节上的处理，让我这个轻度强迫症患者实在是无法接受。所以，就自己着手对其进行修改。调节侧边栏，图像加动画，修正颜色显示，添加回到顶部……最后，它大概就长成如下的样子了。

![首页](/assets/images/2015-10-14/1.jpg)
_首页，修正了侧边栏的不对称_

![标签页](/assets/images/2015-10-14/2.jpg)
_便签页，修正了颜色的不搭_

![全屏](/assets/images/2015-10-14/3.jpg)
_全屏显示方式_

![回到顶部](/assets/images/2015-10-14/4.jpg)
_添加了回到顶部按钮和头像鼠标悬停旋转特效_


## 黑白

我以为我会一直使用那个Theme了，而且也确实花了不少时间去维护它。但是，最后我还是不得不放弃了。原因有三：

1. 绿色这颜色，我真的不能忍
2. 代码风格实在是太乱了
3. 找到了一个让我无法抗拒的主题

对了，就是现在使用的这个主题了。改自[闫肃的博客](yansu.org),无论是配色，还是动态效果，都完全符合我的心意！黑白的主色调，红绿的动态颜色，简约而又不呆板，低调又不失华丽，真的很赞！     

这个主题还有一个比较隐秘的小功能，就是当鼠标**悬停**在**靠近右边栏处**时，会侧滑出文章目录结构。

![文章目录触发器](/assets/images/2015-10-14/5.jpg)
_鼠标停留在图中黄色阴影部分会触发侧滑出目录_

![文章目录](/assets/images/2015-10-14/6.jpg)
_点击目录中链接会滑动到相应位置_


## 写在最后

纵观自己这几次更换Blog，发觉有个共同之处。那就是——**修改博客**。虽然只是简单的4个字，但其间所耗费的时间，真的太多了。我自认为是个有点强迫症的人，不能忍受些许的瑕疵。就像现在这个主题，我不太喜欢它的代码显示的颜色搭配。    

但是，这次我却选择默默地接受了，因为在对于前端的某些技术不是特别熟悉甚至不懂的情况下，盲目地修改，对身心健康都是一种极大地**摧残**，而且，时间和精力上地大量投入往往也只是证明了这只会是**弄巧成拙**。     

所以，写下这篇博文，告诫自己两点：

1. 自己心中无所谓完美的标准，要学会改变自己的眼光，接受“瑕疵”，因为Theme设计者是专业的，我应该学会接受他/她的设计，而不是去盲目地修改。
2. 要学会分清主次。博客重在内容而非展现的形式，要专注于内容，需知人的精力有限。


