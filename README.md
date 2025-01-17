 BeautifulRefreshLayout
=============================================================================================================================


众多优秀的下拉刷新（除了我写的之外T_T）
-----------------------------------------------------------------------------------------------------------------------------
说起下拉刷新，好像经历一段历史的洗礼。。。

(1)在我刚学android的时候，用的是XListView,在github上搜索有[MarkMjw/PullToRefresh](https://github.com/MarkMjw/PullToRefresh),根据Maxwin的XListView改造而来，完善下拉刷新上拉加载更多的功能并实现自动刷新以及自动加载等功能， 并增加对ScrollView的支持。 原XListView参考链接：https://github.com/Maxwin-z/XListView-Android(听说原作者停止维护了)
![](https://camo.githubusercontent.com/d5987bf40a04dc9894fb0ea814515088b8afd7d6/68747470733a2f2f7261772e6769746875622e636f6d2f4d61726b4d6a772f50756c6c546f526566726573682f6d61737465722f53637265656e73686f74732f312e706e67)

(2)然后又学了[chrisbanes/Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh)的那个库，这个库牛逼到要死，支持ListView、ExpandableListView、GridView、WebView、ScrollView、HorizontalScrollView、ViewPager、ListFragment、、、

![](https://github.com/chrisbanes/Android-PullToRefresh/raw/master/header_graphic.png)

自己也侮辱了这个库，改的乱七八糟[https://github.com/android-cjj/ComicReader/tree/master/YinHunPulltoRefreshLibrary](https://github.com/android-cjj/ComicReader/tree/master/YinHunPulltoRefreshLibrary)，增加了支持瀑布流刷新的功能和下拉动画效果的。。。。

![](https://camo.githubusercontent.com/1b016544f28f6abe5775f9b8fdde4ece8c874263/687474703a2f2f7777772e61706b6275732e636f6d2f646174612f6174746163686d656e742f666f72756d2f3230313530342f31342f3039313630366570766f63636e6e38376f67387a38742e706e67)

（3）那时候看了知乎的客户端，下拉刷新很炫，查了下是用什么实现的，最终知道是用[chrisbanes/ActionBar-PullToRefresh](https://github.com/chrisbanes/ActionBar-PullToRefresh)的库可以实现那种效果，又去学了，啊哈哈，然而过些日子也没见人用了，啊哈哈哈

![](https://github.com/chrisbanes/ActionBar-PullToRefresh/raw/master/header.png)

(4)这时候google也有自己的下拉控件SwipeRefreshLayout，刚出来的效果，一条加载直线，个人觉得，一般到要死。[stormzhang/SwipeRefreshLayoutDemo](https://github.com/stormzhang/SwipeRefreshLayoutDemo)写了demo。

![](https://camo.githubusercontent.com/9c0181efd67b9b7f080a1526311eba64485539c2/687474703a2f2f73746f726d7a68616e672e6769746875622e696f2f696d6167652f5377697065526566726573684c61796f75742e676966)

android 5.0之后效果是个加载圆圈,还可以接受了，现在很多应用都用这个

![](https://camo.githubusercontent.com/736dc88d160cc23793bc8193bbbe7b9009d5501e/687474703a2f2f7777332e73696e61696d672e636e2f626d6964646c652f3564343330393737677731656c6b357237736b73756732306234306a726232392e676966)

(5)这时又看到了[baoyongzhang/android-PullRefreshLayout](https://github.com/baoyongzhang/android-PullRefreshLayout),This component like SwipeRefreshLayout, it is more beautiful than SwipeRefreshLayout.就是比google的跟漂亮。呵呵!

![](https://raw.githubusercontent.com/baoyongzhang/android-PullRefreshLayout/master/demo.gif)

(6)同时，这里也要提下[liaohuqiu/android-Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh),已经强大到什么控件都能适用刷新了，相信你也听过了

![](https://camo.githubusercontent.com/88cdf877aa0a1fb19506ecf3404447eba59e68cc/687474703a2f2f737261696e2d6769746875622e71696e6975646e2e636f6d2f756c7472612d7074722f6175746f2d726566726573682e676966)

(7)看过最有创意的下拉刷新[FlyRefresh](https://github.com/race604/FlyRefresh)，一只飞机飞啊飞，然而并没有什么卵用.....

![](https://github.com/race604/FlyRefresh/blob/master/images/flyrefresh.gif)

(8)material设计已经深入到开发者的心里，然后 我看到了A pull-down-to-refresh layout inspired by Lollipop overscrolled effects
[allan1st/JellyRefreshLayout](https://github.com/allan1st/JellyRefreshLayout),我这个也是看人家的代码实现的，十分感谢，啊哈哈

![](https://github.com/allan1st/JellyRefreshLayout/blob/master/images/preview.gif)

(9)最近看的下拉刷新也是挺奇怪的，就比如[recruit-lifestyle/BeerSwipeRefresh](https://github.com/recruit-lifestyle/BeerSwipeRefresh)啤酒下拉刷新和[recruit-lifestyle/WaveSwipeRefreshLayout](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)水滴下拉刷新...

![](https://github.com/recruit-lifestyle/BeerSwipeRefresh/blob/master/sc/animation_beer.gif)
![](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout/blob/master/sc/animation.gif)

(10)这个是网友推荐的[SuperSwipeRefreshLayout](https://github.com/nuptboyzhb/SuperSwipeRefreshLayout),顾名思义，是扩展自SwipeRefreshLayout。
![](https://github.com/nuptboyzhb/SuperSwipeRefreshLayout/raw/master/demo.gif)

(11)这个是Yalantis公司开发的下拉刷新，其中它的很多东西动画这块，做的非常漂亮[Yalantis/Phoenix](https://github.com/Yalantis/Phoenix)
![](https://camo.githubusercontent.com/d406ac5a03a2b1fa5cf41fadc8d2408cb8709bdc/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3132353035362f73637265656e73686f74732f313635303331372f7265616c6573746174652d70756c6c5f312d322d332e676966)

[Taurus](https://github.com/Yalantis/Taurus)又是飞机飞啊飞...
![](https://camo.githubusercontent.com/3a24e22eb3f8338573dba0701c089c12f6b70f11/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3132353035362f73637265656e73686f74732f313632333133312f746f7572732d70756c6c2d616972706c616e655f322d322d332e676966)

(12)[tuesda/CircleRefreshLayout](https://github.com/tuesda/CircleRefreshLayout)的下拉刷新，动画做的很不错，设计图来源[https://dribbble.com/shots/1797373-Pull-Down-To-Refresh](https://dribbble.com/shots/1797373-Pull-Down-To-Refresh)

![](https://github.com/tuesda/CircleRefreshLayout/blob/master/gif/circlerefresh.gif)

(13)[BeautifulRefreshLayoutForFood](https://github.com/android-cjj/BeautifulRefreshLayout/tree/BeautifulRefreshForFood)

看到一个很漂亮的美食下拉刷新[（来源地址）](https://dribbble.com/shots/2096383-Pull-To-Refresh-V2?list=users&offset=1) ，可惜技术水平菜菜的，只能模仿一下下，啊哈哈。。。[源码下载地址download](https://github.com/android-cjj/BeautifulRefreshLayout/tree/BeautifulRefreshForFood)

![](http://www.apkbus.com/data/attachment/forum/201508/06/101826dztai4gnnfmgmuql.gif)

(14)[BeautifulRefreshLayoutForNaruto](https://github.com/android-cjj/BeautifulRefreshLayout/tree/BeautifulRefreshForNaruto)

闲着蛋疼，写了个血轮眼下拉刷新的，虽然火影漫画完结了，但是动画还在继续，真的是挂漫天飞。。。。[(源码下载地址download)](https://github.com/android-cjj/BeautifulRefreshLayout/tree/BeautifulRefreshForNaruto)

![](http://www.apkbus.com/data/attachment/forum/201508/21/155921wqhrrbufrj6ghhet.gif)

(15)[bingoogolapple/BGARefreshLayout-Android](https://github.com/bingoogolapple/BGARefreshLayout-Android)多种下拉刷新效果、上拉加载更多、可配置自定义头部广告位...

![](https://camo.githubusercontent.com/f609f7944250a6607e5fdec8b12b3156df569cd7/687474703a2f2f37786b39646a2e636f6d312e7a302e676c622e636c6f7564646e2e636f6d2f726566726573686c61796f75742f73637265656e73686f74732f726566726573686c61796f7574312e676966)


 (16)[BeautifulRefreshLayoutForGirl](https://github.com/android-cjj/BeautifulRefreshLayout/tree/BeautifulRefreshForGirl)

这是一个小清新的下拉刷新，纯代码绘制，无需任何图片，Recyclerview中item展示的妹子图来自[http://gank.io/](http://gank.io/)

设计图来源，当然我实现的效果做了一些修改，希望你喜欢，呵呵。。。[源码下载地址download](https://github.com/android-cjj/BeautifulRefreshLayout/tree/BeautifulRefreshForGirl)
[pull to refresh by Michael Lanning](https://dribbble.com/shots/1936194-Pull-To-Refresh)
截图
-------------------------------------------------------------------------------------------------------
![](http://www.apkbus.com/data/attachment/forum/201509/01/142628nzivid67j09kfnj6.png)
![](http://www.apkbus.com/data/attachment/forum/201509/01/142630dphjpz3m3ruyzrxy.png)

![](http://www.apkbus.com/data/attachment/forum/201509/01/142631fyqq802qmncadxjw.png)
![](http://www.apkbus.com/data/attachment/forum/201509/01/142632xzg7oz7f2j5j5o88.png)

(17)[BeautifulRefreshLayoutForRain](https://github.com/android-cjj/BeautifulRefreshLayout)

这是一个下雨刷新，你没听错，确实一刷新就下雨，为什么会出现，只是我的好奇心而做的东西，见怪不怪了，呵呵。。。

![](http://www.apkbus.com/data/attachment/forum/201509/01/140049ia4d2w588wkvnkkl.gif)

(18)[Android-MaterialRefreshLayout](https://github.com/android-cjj/Android-MaterialRefreshLayout)是我最近写的, it is more beautiful and powerful than SwipeRefreshLayout ,  下拉刷新拥有侵入式，非侵入式，覆盖式，非覆盖式，自动刷新，上拉加载更多,自动加载等功能......

![](http://www.apkbus.com/data/attachment/forum/201509/11/095859kp297mjmj2php5pm.jpg)



写在最后
=================================================================================
这个仓库我会一直维护，有时间也会写一些比较有意思的下拉刷新，只是技术有限，不要吐槽给建议就好，呵呵。。。同时，也希望你们能介绍一些比较好的下拉刷新的库给我，让更多人知道有这个东西，大家一起交流学习，一起进步。欢迎随时关注，记得star哦，呵呵！

随意说说
-----------------------------
刚建了个[github小伙伴交流群](http://t.cn/RyiVjnv)(477826523),有兴趣的朋友可以加进来的...小小要求：github有至少7个关注者或者开源库有7颗星星的...

      ****************************转载请注明出处,不然我咬你哦！************************

[about me](http://android-cjj.github.io/)
------------------------------------

License
=======

    The MIT License (MIT)

	Copyright (c) 2015 android-cjj

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.









