# BYD_AI_Helper
接入了AI大模型的语音助手，可用于车机。
> - 手机上也可以运行，但是每个手机都有语音助手(比如超级小爱)，所以其实用处不大。
> - 目前在比亚迪秦L上测试完成了，其他车型欢迎自测。
> - 目前已经接入了kimi、豆包、ChatGPT，均为免费使用，后续还会增加更多并支持可选。

> **推荐的介绍网页：https://xfxuezhang.cn/index.php/archives/1368/**

# 背景说明   
**为什么需要​​​AI大模型语音助手？内置的小迪不行吗？**  
- 其实还是有用的，比如路上遇到鱼骨线等不知道什么意思，内置的语音助手是不会给答案的，用过的都知道。或者开车路过一个地方忽然想了解这个地方的历史或者特色，都可以问大模型。而现在的豆包、kimi等这些软件虽然好用，但都没有适配车机。想要使用的时候，都要手动去打开软件，再去点打电话，比较麻烦，高速上还不安全，如果在导航那用完还得手动退出并切换到导航。这些软件比较适合连续聊天。  
- 而AI语音助手的话，则可以一键触发或者通过方控即可触发，避免了一系列的启动操作，而且支持联网，回答的内容又新又全。唯一的缺点是接口可能会失效，不过这个问题会在后续的更新中修复。

---

# 触发方式  
> 注意：可以在gpt_helper/config.txt中修改配置项.  
1、当`mode=once`时，每次运行只触发一次，运行完就会结束。  
2、当`mode=listen`时，软件会一直在后台监听按键，长按语音键会触发运行。  
3、若只想让它运行一次(即`mode=once`)，但是又想通过方控触发，可以使用“迪加app”或“BYD按键助手+touchtask”的方式。  

---

- 下载链接(密码:xfxz)：https://xfxuezhang.lanzouo.com/b01ynrw4le  
- 演示视频：https://www.bilibili.com/video/BV1hiKcefECh/

欢迎加群，后续版本的更新与维护会发在群里：  
<img src="https://cccimg.com/view.php/63f0f0562b057648bf796c1dd433e9c3.jpg" alt="QQ图片" style="width: 400px; display: block; margin: 0 auto;">

---

# 更新历史
- **v1.1.0.2**
1、新增长按音量键触发，不再需要迪加 (需设置mode=listen)。
2、新增kimi、豆包、ChatGPT等多个GPT接口。
3、新增语音指令退出助手(语音为“切换模式”)。

- **v1.1.1.0**
1、优化语音响应速度。
2、修复启动闪退。

- **v1.1.1.1**
1、新增播报音色选择(在配置文件中修改)。
2、新增语音指令切换模式(语音为“切换模式”)。


