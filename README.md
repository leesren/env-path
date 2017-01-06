# env-path


# 常见的环境变量配置

## Android 开发环境变量

1. 下载JDK [链接](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 

2. 配置SDK 
    * 配置代理,下载包 [参考](http://www.androiddevtools.cn/)
    * [mac 下 android studio 的离线gradle极速配置方法](http://www.cnblogs.com/thtlovelife/p/5872801.html)
    * [最详细的mac下Android studio配置gradle的路径](http://blog.csdn.net/u013634213/article/details/51120783)
    * [ 在mac上安装gradle（超详细，直接按步骤操作即可轻松搞定）](http://blog.csdn.net/u014749862/article/details/48982925)

        gradle 的配置比较隐蔽，在Mac上，.gradle 存放的路径是 `/Users/luketang/.gradle`, 如果看不到 `.gradle` 文件夹，使用快捷键进行切换 显示和隐藏
 `cmd + shift + .` 可以做切换, 然后进入 `/Users/zenberge/.gradle/wrapper/dists/gradle-2.4-all/6r4uqcc6ovnq6ac6s0txzcpc0/gradle-2.14-all.zip`, 
 放置下载对应的 `gradle-2.14-all.zip` ，这样就可以跳过下载的过程。


 ## react-native 开发环境变量配置
 1. 先按官网配置Mac [官网](http://reactnative.cn/docs/0.40/getting-started.html#content) ，[参考1](http://blog.csdn.net/jyt199011302/article/details/53912278)
    * 问题1    error: unable to find utility “instruments”, not a developer tool or in PATH
    
     打开Xcode，` Preferences... > Locations > Command Line Tools ` 选择 相应的命令行工具 如 `Xcode 7.3.1 (D73434)`