一套开源Android游戏SDK（An open AndroidGame Channel SDK）
==
项目简介（Directions for use）：
----
  
> 大家好，我是骑小猪看流星~是一名普通的Android开发。<br/>
    前不久入职于一家游戏研发公司，公司部门给我的开发需求是研发H5游戏SDK和对接H5渠道SDK（对于只有App研发的我来说，其中经历和酸甜苦辣那可是一把鼻涕一把泪。<br/>  
    不乏笔者牺牲周末时间去熟悉该业务的朋友公司向他取经讨论技术方案，画UML图等。要命的是各大搜素引擎可查询SDK资料几乎就是打广告打广告，免费提供解决技术方案（也就是源代码）的参考实在太少，这根本不能符合我大Android集思广益忠于开源的灵魂好嘛。 所以，本项目不仅是针对未来有类似研发需求的朋友传道解惑，节约时间少走弯路，而且更主要的是揭开Android游戏SDK的神秘面纱。
  
     然后，你可能懵逼了，你不是开发H5游戏SDK和对接H5渠道SDK嘛，怎么扯Android上面来了。是的，的确跟我们大Android有关。
  
     关于上面的问题，可以移步下面的链接，里面有详细的说明，会让你了解什么是游戏SDK，游戏SDK的开发要点，使用技巧有那些。
  
[进一步的说明](https://www.jianshu.com/p/8b9d82560a67)

一般来说，Android游戏SDK有以下设计接口（常用）：
(The Android game SDK is a common design interface/function)

* 初始化  (init)
* 登录  (login)
* 支付  (pay)
* 显示浮标 (show window)
* 隐藏浮标 (hide window)
* 提交用户信息 (submit user info)
* 注销  (logout)
* 切换账号 (switch account)
* Activity生命周期处理（Activity lifecycle ）
* 实名制验证 (Real-name verification)
* 基于渠道业务需求拓展(channel expand interface)
* 基于渠道业务需求拓展(channel expand interface)


      既然提供了常用设计接口，我们需要基于自家后台和业务需求去编写相对应的功能，供对接方使用。
      
      更常见的做法是通过接口回调，去告知调用者该接口调用成功or调用失败。接口调用成功以后，会从中获取到什么数据。
    
      可能你已经晕了，没事，可以先看一下上面的说明链接及项目代码，这样可以更好的理解游戏SDK。
      

#### 假设你想快速开发一款渠道游戏SDK，只需要：
* 拉取本项目代码
* 更改UI
* 替换成自家的后台接口（依据业务需求去开发接口）
* 将自己写好的代码，打成jar包，提供相应对接的资源文件（如：渠道参数，布局文件，文字图片；清单文件里面的权限，四大组件基本配置等）写成技术对接文档
* 写一套测试Demo，给游戏技术去对接测试使用即可。


      **可能你连对接文档都懒得写，没事，本项目SDK的使用文档，我也为大家准备了一个简易版本,也就是项目里面的use_sdk_game.text。所以，你懂的。**

      **如果你down了笔者的代码之后，会惊奇的发现，笔者的代码就是方便给大家Copy的。（全部是gamesdk_xxx)**
      

##### 想说的话：

    君子性非异也，善假于物也。
    
    能人之所以高于一般人，是因为他能善于利用外物。善于利用已有的各种条件，是能人成功的一个重要途径。
    
    开源的本质就是善假于物，汲人所长，补己所短。

##### 最后：

    千里之行，始于足下。

    希望和大家一起学习成长共同进步,早日达到技术之巅！

##### Ps：

    本项目没有使用到任何商业接口、请放心使用！

    著作权归作者所有,转载请注明作者, 商业转载请联系作者获得授权，非商业转载请注明出处(开头或结尾请添加转载出处，添加原文url地址)
    
    文章请勿滥用,也希望大家尊重笔者的劳动成果,谢谢。

##### 联系方式：

    对本项目有任何问题，请直接联系笔者（非诚勿扰）

    QQ：2172410367(骑小猪看流星)

    email：yijiutanzuowu1992@163.com


