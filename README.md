# WechatHook-Dusan
Enjoy hooking,by Xposed,Root,Accessibility,and so on...

开发辅助工具，类似聊天机器人，自动抢红包，自动发XX圈这样的功能。Xposed可以开发很多有趣的应用，但必须花足够时间研究所要hook的App源码，反编译后的都是高度混淆的代码，看起来太痛苦了，本项目开源学习，仅供研究和学习技术，请不要做任务商业用途，与本人无关。

hook，需要根据需要去深入！！

![auto-wechat-dusan.png](http://upload-images.jianshu.io/upload_images/2001922-59bb02f4ed2cfe65.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## About 

这是一个有趣的项目，探索android流行的黑科技，专注研究和开发wx助手。持续更新，感兴趣的话，请Star or Fork一下吧：

[https://github.com/duqian291902259/WechatHook-Dusan](https://github.com/duqian291902259/WechatHook-Dusan)

工具链：Mac，Android Studio，Root的手机，业余挖掘技术的魅力。
上图源码还没有同步上来，目前可以参考我下面的说明和源码。

## Features

![wechat-hook-dusan](https://github.com/duqian291902259/WechatHook-Dusan/blob/master/screenshot/wechat-hook-dusan.png)


##### 1，本项目应用了xposed框架，实现wx hook，可以自动智能回复聊天信息，实现聊天机器人的功能，所以需要root权限。

##### 2，如果没有root权限，本项目进行了一些有趣尝试。应用android辅助功能，自动添加附近的人为好友，自动打招呼，自动抢红包等。

##### 3，修改wx的位置信息，发朋友圈可以装逼了，出国so easy，内置google地图，需要翻墙哈。

##### 4，可以刷跳一跳，小游戏原来可以这样操作，但需要Root权限，99分！

#### 5，Wechat Hook，技术限制了我们更多的想象。。。

![wenchat-tiaotiao](https://github.com/duqian291902259/WechatHook-Dusan/blob/master/screenshot/wenchat-tiaotiao.png)


## Tips
hook 某个app，都是针对某个版本进行的，因为需要反编译apk，分析源码查找hook点，才能改变原有app的执行逻辑或者改变输入输出值，本项目开发时支持的wx版本较早：6.3.32，无论哪个版本，原理是相同的，如果针对新版开发，可以自行探索本demo，相信你可以从代码中找到启发。

打开下列链接，下载apk测试：
##### 1，安装release app，用下面链接提供的打包好了的app。

##### 2，已经root过的手机一台，要安装好xposed框架，并加载本项目的WechatHook模块到xposed，重启生效。

##### 3，安装指定版本的apk，目前xposed只针对这个版本哈。

##### 4，如果wx底部tab，发现里面的“扫一扫”变成了“duqian2010@gmail.com"表示hook微信成功了。

[https://github.com/duqian291902259/WechatHook-Dusan/tree/master/hook_release](https://github.com/duqian291902259/WechatHook-Dusan/tree/master/hook_release)

## Future

只有尝试了才能领悟其中的乐趣，因为经历有限，没有hook最新版wx。越早期的版本，业务逻辑相对少，代码量越小，相对容易hook。

免责申明：仅供研究xposed，辅助功能技术用，请勿用做其他用途！

欢迎交流：
duqian2010@gmail.com ,杜小菜，wechat：dusan2010


