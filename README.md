# BYD_AI_Helper
接入了AI大模型的语音助手，可用于车机。
> - 手机上也可以运行，但是每个手机都有语音助手(比如超级小爱)，所以其实用处不大。
> - 目前在比亚迪秦L上测试完成了，其他车型欢迎自测。
> - 目前已经接入了kimi、豆包、ChatGPT，均为免费使用，后续还会增加更多并支持可选。

> 转载请注明出处：小锋学长生活大爆炸[xfxuezhagn.cn]
> 如果本文帮助到了你，欢迎[点赞、收藏、关注]哦~

<img src="https://xfxuezhang.cn/usr/uploads/2025/02/3287715980.png" alt="QQ图片" style="width: 400px; display: block; margin: 0 auto;">

# 软件介绍
接入了AI大模型的语音助手，可用于车机。
> - 手机上也可以运行，但是每个手机都有语音助手(比如超级小爱)，所以其实用处不大。
> - 目前在比亚迪秦L上测试完成了，其他车型欢迎自测。
> - 目前已经接入了kimi、豆包、ChatGPT，均为免费使用，后续还会增加更多并支持可选。


# 为什么需要​​​AI大模型语音助手？内置的小迪不行吗？
其实还是有用的，比如路上遇到鱼骨线等不知道什么意思，内置的语音助手是不会给答案的，用过的都知道。或者开车路过一个地方忽然想了解这个地方的历史或者特色，都可以问大模型。而现在的豆包、kimi等这些软件虽然好用，但都没有适配车机。想要使用的时候，都要手动去打开软件，再去点打电话，比较麻烦，高速上还不安全，如果在导航那用完还得手动退出并切换到导航。这些软件比较适合连续聊天场景。

而AI语音助手的话，则可以一键触发或者通过方控即可触发，避免了一系列的启动操作，而且支持联网，回答的内容又新又全。唯一的缺点是接口可能会失效，不过这个问题会在后续的更新中修复。

# 下载链接
1、固定常用链接：https://xfxuezhang.cn/web/download/    
2、固定备用链接(密码:xfxz)：https://xfxuezhang.lanzouo.com/b01ynrw4le

# 使用说明
- 配置文件在`/sdcard/ai_helper/config.txt`，修改并保存后，重启助手生效。    
- 演示和安装教程：https://space.bilibili.com/37064895/lists/4609181
{bilibili bvid="BV1hiKcefECh/" page=""/}

支持的语音指令：
| 语音指令 | 执行解释 |
| :--: | :--: |
| 退出 | 不管是单次模式还是监听模式，助手都会退出 |
| 切换模式 | 单次模式与监听模式互转，重启助手生效 |
| 打开xx | xx表示安装的应用名称，比如“打开高德地图” |


## 触发方式一：单次+手动
- 配置文件`config.txt`中`mode=once`，即触发一次就执行一次，执行完后就退出。
- 每次手动点击软件来触发运行。
- 比较适用于体验软件，在开车时实际上并不方便。

## 触发方式二：单次+迪加
- 配置文件`config.txt`中`mode=once`，即触发一次就执行一次，执行完后就退出。
- 安装**迪加app**，打开**方控设置**，选择**长按语音键**，输入**“打开应用GPT语音助手”**。
- 适合在开车时+低频使用。

<img src="https://xfxuezhang.cn/usr/uploads/2025/02/1148409041.png" alt="QQ图片" style="width: 400px; display: block; margin: 0 auto;">

<img src="https://xfxuezhang.cn/usr/uploads/2025/02/4277859172.png" alt="QQ图片" style="width: 400px; display: block; margin: 0 auto;">


## 触发方式三：监听模式
- 配置文件`config.txt`中`mode=listen`，即一直在后台监听按键，执行完后就退出。
- **长按语音键**可以触发，不需要额外安装迪加app。
- 这个触发按键可以在配置文件中更改。如果你不知道改改成什么，建议不要去动它。
- 适合在开车时+高频使用。

## 触发方式四：语音唤醒
- 配置文件`config.txt`中`mode=voice`，即触发一次后就进入监听状态，通过语音唤醒。
- 无需安装其他软件，但是会**一直在后台监听录音**以检测唤醒词(本地录音，不会上传数据，放心使用)。
- 目前的唤醒词固定为“呼叫助手”，后期将改为可自定义。



# 交流Q群
- 欢迎加群，后续版本的更新与维护会优先发在群里。
- Q群号：768030842
<img src="https://cccimg.com/view.php/63f0f0562b057648bf796c1dd433e9c3.jpg" alt="QQ图片" style="width: 200px; display: block; margin: 0 auto;">


# 更新说明：
- **v1.0.0.0**  
    1、实现基础功能。  
    2、演示视频：[https://www.bilibili.com/video/BV1hiKcefECh/](https://www.bilibili.com/video/BV1hiKcefECh/)

- **v1.1.0.2**  
    1、新增长按音量键触发，不再需要迪加 (需设置mode=listen)。  
    2、新增kimi、豆包、ChatGPT等多个GPT接口。  
    3、新增语音指令退出助手(语音为“切换模式”)。  
    4、演示视频: [https://www.bilibili.com/video/BV1R3AKe6EfQ/](https://www.bilibili.com/video/BV1R3AKe6EfQ/)

- **v1.1.1.0**  
    1、优化语音响应速度。  
    2、修复启动闪退。  

- **v1.1.1.1**  
    1、新增播报音色选择(在配置文件中修改)。  
    2、新增语音指令切换模式(语音为“切换模式”)。  

- **v1.1.1.2**  
    1、新增小爱同学语音引擎(需要在配置文件中修改voice_engine=xiaoai，并安装“小爱系统语音引擎”，并且在车机上该引擎app也需要“运行后台自启动”和“加速白名单”权限。  
    2、小爱系统语音引擎下载：[https://xfxuezhang.lanzouo.com/iagPH2o1exbg](https://xfxuezhang.lanzouo.com/iagPH2o1exbg))。  
<img src="https://xfxuezhang.cn/usr/uploads/2025/02/3684260241.png" alt="QQ图片" style="width: 400px; display: block; margin: 0 auto;">

- **v1.1.1.3**  
    1、修复一些问题。  

- **v1.1.1.4**  
  1、新增播报语速调整(在配置文件中修改，默认1.0)。  
  2、新增可修改语音键keycode(在配置文件中修改，默认语音键)。  

- **v1.1.1.5**  
  1、新增播报时自动调节音量(配置文件中的voice_volume，默认未开启)。  
  2、新增简单地车机控制，如“打开高德地图”、“打开QQ音乐”(已安装的软件名即可)。  

- **v1.1.1.6**  
  1、修复部分车机无法使用小爱语音引擎 (即配置文件中voice_engine=xiaoai，默认url方式)；  
  2、稍微优化一点响应速度 (根据车机性能的不同，启动可能还是会有一点慢)；  

- **v1.1.1.7**  
  1、新增语音唤醒功能 (即配置文件中mode=voice，默认once方式。使用此功能需要安装小爱语音引擎)；  
  2、演示视频：[https://www.bilibili.com/video/BV1VwQNYBEVQ/](https://www.bilibili.com/video/BV1VwQNYBEVQ/)  



