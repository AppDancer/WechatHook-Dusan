# WechatHook-Dusan
Enjoy hooking wechat by Xposed...Accessibility...and so on

开发微信辅助工具，聊天机器人，自动抢红包，自动发朋友圈这样的功能。Xposed可以帮助我们开发很多有趣的插件，难点是要花足够时间研究所要hook的App源码，寻找hook点，看混淆的代码是在太痛苦了，希望该项目对大家有所帮助和启发。没有诸神那么牛逼的框架，都是一点点积累玩起来。。。

![auto-wechat-dusan.png](http://upload-images.jianshu.io/upload_images/2001922-59bb02f4ed2cfe65.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## About 

这是一个有趣的项目，探索android流行的黑科技，专注研究和开发微信助手。持续更新，感兴趣的话，请Star or Fork一下吧：

[https://github.com/duqian291902259/WechatHook-Dusan](https://github.com/duqian291902259/WechatHook-Dusan)

本人工具链：Mac，Android Studio，Root的手机，xposed等，业余挖掘技术的魅力。
部分源码未同步，目前可参考以下说明，也可以star源码pull request bugs。

## Features

![wechat-hook-dusan](https://github.com/duqian291902259/WechatHook-Dusan/blob/master/screenshot/wechat-hook-dusan.png)


##### 1，本项目应用了xposed框架，实现微信hook，可以自动智能回复聊天信息，实现聊天机器人的功能，所以需要root权限。

##### 2，如果没有root权限，本项目依然有针对微信的有趣尝试。应用android辅助功能，自动添加附近的人为好友，自动打招呼，自动抢红包等。

##### 3，修改微信的位置信息，发朋友圈可以装逼了，出国so easy，内置google地图，需要翻墙哈。

##### 4，可以刷跳一跳，小游戏原来可以这样操作，但需要Root权限，99分！

#### 5，Wechat Hook，技术限制了我们更多的想象。。。

![wenchat-tiaotiao](https://github.com/duqian291902259/WechatHook-Dusan/blob/master/screenshot/wenchat-tiaotiao.png)


## Tips
hook 某个app，都是针对某个版本进行的，因为需要反编译apk，分析源码查找hook点，才能改变原有app的执行逻辑或者改变输入输出值，本项目开发比较早，支持的微信版本为：6.3.32 和6.5.7,新版本业余再跟进吧，如果要开发，可以自行探索或加我交流，相信你可以从代码中找到启发。

打开下列链接，下载apk测试：
##### 1，安装release app，用下面链接提供的打包好了的app。

##### 2，已经root过的手机一台，要安装好xposed框架，并加载本项目的WechatHook模块到xposed，重启生效。

##### 3，安装weixin，该项目只是针对特定版本哈。

##### 4，如果微信底部tab，“通讯录”改成了“杜小菜”，发现里面的“扫一扫”变成了“duqian2010@gmail.com"表示hook微信成功了。

[https://github.com/duqian291902259/WechatHook-Dusan/tree/master/hook_release](https://github.com/duqian291902259/WechatHook-Dusan/tree/master/hook_release)

## Future

本项目以前开发的，也学习和借鉴了很多前辈的经验，感谢。

欢迎交流：
duqian2010@gmail.com ,杜小菜，微信：dusan2010


