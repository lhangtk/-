# Android-open-project-for-TM

1
拖动刷新pulltorefresh
一个强大的拉动刷新开源项目，支持各种控件下拉刷新，ListView、ViewPager、WebView、ExpandableListView、 GridView、ScrollView、Horizontal ScrollView、Fragment上下左右拉动刷新。并且它实现的下拉刷新 ListView在item不足一屏情况下也不会显示刷新提示，体验更好。
项目地址：https://github.com/chrisbanes/Android-PullToRefresh

2
图片多手势处理PhotoView
支持双击或双指缩放的ImageView，在ViewPager等Scrolling view中正常使用，支持ViewPager，同时支持单个ImageView
项目地址：https://github.com/chrisbanes/PhotoView

3
各种工具 xUitls
包含DbUtils、ViewUtils、HttpUtils、BitmapUtils四大模块，基于Afinal的二次封装。
项目地址：https://github.com/wyouflf/xUtils

4
消息处理 EventBus
项目地址：https://github.com/greenrobot/EventBus
特点：(1) 支持在不同类型的线程中处理订阅，包括发布所在线程，UI线程、单一后台线程、异步线程
(2) 支持事件优先级定义，支持优先级高的订阅者取消事件继续传递，支持粘性事件，是不是跟系统的有序广播、粘性广播很像啊
(3) 不是基于annotations
(4) 性能更优
(5) 体积小
(6) 支持单例创建或创建多个对象
(7) 支持根据事件类型订阅

5
图片缓存Universal-Image-Loader
图片缓存，目前使用最广泛的图片缓存，支持主流图片缓存的绝大多数特性。
项目地址：https://github.com/nostra13/Android-Universal-Image-Loader

6
网络请求Android-async-http
Android异步Http请求
项目地址：https://github.com/loopj/android-async-http
文档介绍：http://loopj.com/android-async-http/
特点：(1) 在匿名回调中处理请求结果
(2) 在UI线程外进行http请求
(3) 文件断点上传
(4) 智能重试
(5) 默认gzip压缩
(6) 支持解析成Json格式
(7) 可将Cookies持久化到SharedPreferences

7
PDF解析 mupdf
轻量快速的pdf解析器
官方地址：http://mupdf.com/ 

8
图片裁剪android-crop
简单易懂的图片裁剪
项目地址：https://github.com/jdamcd/android-crop
效果图：
![image](https://raw.githubusercontent.com/jdamcd/android-crop/master/screenshot.png)

9
网络相关Volley
Google提供的网络通信库，使得网络请求更简单、更快速
项目地址：https://android.googlesource.com/platform/frameworks/volley
Volley可是说是把AsyncHttpClient和Universal-Image-Loader的优点集于了一身，既可以像AsyncHttpClient一样非常简单地进行HTTP通信，也可以像Universal-Image-Loader一样轻松加载网络上的图片。除了简单易用之外，Volley在性能方面也进行了大幅度的调整，它的设计目标就是非常适合去进行数据量不大，但通信频繁的网络操作，而对于大数据量的网络操作，比如说下载文件等，Volley的表现就会非常糟糕。



10
滚轮列表AndroidWheel
项目地址：https://code.google.com/p/android-wheel/
效果图：
![image](https://camo.githubusercontent.com/e9a9430ac807dcfcde5ebc407684a8b7459bb9bd/687474703a2f2f6661726d362e737461746963666c69636b722e636f6d2f353533322f31313632313532383738365f323230633034306261355f6f2e6a7067)


11
图表工具MPAndroidChart
强大的图表绘制工具，支持折线图、面积图、散点图、时间图、柱状图、条图、饼图、气泡图、圆环图、范围（高至低）条形图、网状图及各种图的结合；支持图的拖拽缩放；支持 Android 2.2 以上，支持横纵轴缩放，多指缩放，展现动画、高亮、保存到 sdcard、从文件读取图表
项目地址：https://github.com/PhilJay/MPAndroidChart
