# DaemonService

Android中用jni实现的守护进程，达到常驻内存的作用。

前段时间写了卸载反馈的功能后，有不少人联系想要实现服务常驻内存的`Demo`，其实他俩差不多。
我这里就简单的实现了下。


###该功能只供学习讨论使用，强烈要求大家不要应用到实际项目中，还手机一个健康的环境。

目前的实现方式非常不好，每`1s`的轮训会消耗系统大量资源。还有很多需要改进的地方，大家自行研究吧。

---

- 邮箱 ：charon.chui@gmail.com  
- Good Luck! 

