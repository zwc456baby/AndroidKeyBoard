# Android TV 开发框架

官方论坛：http://www.androidtvdev.com/ 

我的个人博客：https://blog.csdn.net/qw85525006/category_6228458.html [欢迎一起学习]

QQ群：522186932 ()
QQv2.0群: 468357191 ()

一些Android tv开发总结：http://git.oschina.net/kumei/AndroidTVWidget/wikis/Home

![运行DEMO](https://git.oschina.net/hailongqiu/AndroidTVWidget/raw/master/doc/demo.gif?dir=0&filepath=doc%2Fdemo.gif&oid=f30160b097d319e464d106b39c6b5414acc9fdac&sha=9de6aa98d14c3c80d88f4dfb93a5064ba2614a81 "在这里输入图片标题")

Leanback 框架(类似谷歌的Leanback,更简直，更方便):
![输入图片说明](http://git.oschina.net/uploads/images/2016/0911/112714_3027c40f_111902.gif "在这里输入图片标题")


![输入图片说明](http://git.oschina.net/uploads/images/2016/0528/012952_10a76d5c_111902.gif "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0528/013009_c97c4191_111902.gif "在这里输入图片标题")

菜单框架：


## 整体目录结构

![输入图片说明](http://git.oschina.net/uploads/images/2016/0525/144035_11b9989b_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0525/144049_4f5dbe94_111902.png "在这里输入图片标题")

*AndroidTvWidet 目录是TV开发框架的 库文件.

*demo 目录是 例子.

*doc 目录是存放文档的.

*Tool 目录 是 屏幕像素转换工具.

## AndroidTVwidget库目录结构

![框架目录结构](http://git.oschina.net/uploads/images/2016/0505/155151_939fc32a_111902.png "在这里输入图片标题")

com.open.androidtvwidget.adapter : 标题栏的adapter基类.

com.open......bridge : MainUpView的依赖类，比如移动的动画都在这里实现的

com.open.....cache: 缓存

com.open....keyboard: 键盘

com.open....menu : 菜单

com.open.android...recycle : recyclerview 的支持（gridview)

com.open.android...utils:一些常用函数封装

com.open...android..view:一些TV改造的控件.(下面我们将接受这里面的控件使用方法)

API文档：

    http://git.oschina.net/kumei/AndroidTVWidget/attach_files

使用说明: 

   http://git.oschina.net/kumei/AndroidTVWidget/wikis/AndroidTVWidget-use-manual

键盘使用说明:
   
   http://git.oschina.net/kumei/AndroidTVWidget/wikis/Android-TV-如何使用键盘控件(SkbContainer)

项目导入说明:
   
   http://git.oschina.net/kumei/AndroidTVWidget/wikis/AndroidTVWidget-use-manual(Android-Studio)

   http://git.oschina.net/kumei/AndroidTVWidget/wikis/AndroidTVWidget-use-manual(Eclipse导入)


 欢迎进入 TV开发，希望大家不断的分享代码，一起进步，谢谢. （hailongqiu 356752238@qq.com）

欢迎加入QQ群，一起学习，一起进步，这里有很多TV方面的高手噢。
  
![输入图片说明](http://git.oschina.net/uploads/images/2016/0223/094451_e49419a7_111902.png "在这里输入图片标题")
 
![输入图片说明](http://git.oschina.net/uploads/images/2016/1027/104438_314dcab5_111902.png "在这里输入图片标题")

天天加班加点，欢迎支持(用于网站论坛维护)

![天天加班加点，欢迎支持](http://git.oschina.net/uploads/images/2016/0310/133650_1cc016cc_111902.png "天天加班加点，欢迎支持")![输入图片说明](http://git.oschina.net/uploads/images/2016/0509/155346_0f462db8_111902.png "在这里输入图片标题")


##Tab 测试DEMO图片.
    
![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/110716_e9f61513_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/110827_505fcc9c_111902.png "在这里输入图片标题")

![GridViewTV](http://git.oschina.net/uploads/images/2016/0428/112433_94b26833_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/110937_f5e73cf4_111902.png "在这里输入图片标题")

[ViewPager-DEMO]

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/111118_325845c8_111902.png "在这里输入图片标题")

[键盘-DEMO]

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/111129_38af8a29_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0422/204409_fc65ce11_111902.png "在这里输入图片标题")

## 后期加入
   
   网络加载布局

   
## 感谢开源[参考代码]
<p>
<a href="https://github.com/XiaoMi/android_tv_metro">XiaoMi android_tv_metro </a>
</p>
<p>
<a href="https://github.com/lf8289/BorderViewDemo">BorderViewDemo</a>
</p>

## 感谢支持


[![在这里插入图片描述](https://images.gitee.com/uploads/images/2020/0521/011337_c08fa48c_111902.jpeg)



## 版本更新

v1.4.0 

*添加recyclerview的支持

*修复gridviewTv 更新数据崩溃

*修改GridViewTV demo

*修复键盘DEMO 崩溃

*倒影控件添加间距接口

*整理移动动画的函数