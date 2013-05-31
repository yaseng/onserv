onserv
======
     jQuery.onServ 1.0

简单方便的在线客服展示插件 jQuery.onServ 高空科技出品
概述

    项目发布地址 www.uauc.net/product/onserv.html
    演示地址 www.uauc.net/product/onserv.html
    Google项目 code.google.com/p/onserv
    交流qq群 209547092 (高空科技交流群)

       jQuery.onServ 是一款简单方便的在线客服jQuery 插件,可以使任意html实现弹出展示在线客服效果,
     
      可以自定义内容,简单配置出多个弹出动作特效,设置位置和样式.

使用

     
      $("#serv").onserv({
        top:70,            // 高度
     	 left:-156,          //缩进
     	 fx:"easeInOutBack",       //动作特效  
     	 speed:150,         //弹出时间
     	 opacity:0.9        //透明度
     	 });
      

    可以使用任意html区块比如demo页面中的 serv div(内含图片psd) 

弹出效果

    动画效果采用 jQuery.easing 插件 可以自定义各种效果

     
    方法介绍：
         def：默认方式设置
         swing：默认方式加载
         Quad：二次方缓动(t)
         Cubic：三次方缓动
         Quart：四次方缓动
         Quint：五次方缓动
         Sine：正弦曲线缓动
         Expo：指数曲线缓动
         Circ：圆形曲线的缓动
         Elastic：指数衰减的正弦曲线缓动
         Back：超过范围的三次方缓动
         Bounce：指数衰减的反弹缓动
     

关于In、Out、Inout的说明：

easeIn：加速度缓动； easeOut：减速度缓动； easeInOut：先加速度至50%，再减速度完成动画。
更新记录

    jQuery.onServ 1.0
    2012 11 7 实现在线弹出展示功能 兼容各种浏览器

