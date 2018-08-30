# KeYingLove
一件事情，你坚持做了三天，那是心血来潮，你坚持了三个月，那是刚刚上场！你坚持了三年那才算得上事业，如果你做什么事都要求立马有回报，那注定这辈子只能是一事无成，成功路上并不拥挤，因为坚持的人不多！坚持就是胜利，早安，加油！




## 常用工具：
#### 1.LinkMap解析工具：检查每个类占用大小 [LinkMap](https://github.com/huanxsd/LinkMap) 
#### 2.InjectionIII：不用编译就可以看到UI修改 [InjectionIII](https://github.com/johnno1962/InjectionIII) [injectioniii app](https://itunes.apple.com/us/app/injectioniii/id1380446739?mt=12)
```objc
// applicationDidFinishLaunching:
#if DEBUG
[[NSBundle bundleWithPath:@"/Applications/InjectionIII.app/Contents/Resources/iOSInjection.bundle"] load];
#endif
```
在状态栏 InjectionIII 打开你的工程，开启 File Watcher，每次修改文件保存时 Injjection 就开始编译修改过的文件为动态库，想要及时刷新界面，可以在你的类（必须是 NSObject 的子类）中重写 `- (void)injected{}` 方法，来刷新界面。

## 学习笔记：
#### Weex是如何在iOS客户端上跑起来的 [Weex](https://www.jianshu.com/p/41cde2c62b81)

## 代码输出
