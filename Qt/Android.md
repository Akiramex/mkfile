# Qt for Android

[Qt for Android之AndroidManifest.xml详解](https://blog.csdn.net/qq_35241071/article/details/101051259)

[Android之权限（permission）大全](https://blog.csdn.net/s13383754499/article/details/84281151)

qml中控件路径必须加file://例如：

```xml
Image {
	source:"file:///mnt/usbhost1/Config/logo.png"
}
```



Qt5构建安卓项目可以在Kits->Build的步骤更改ABIs，默认为armeabi-v7a



release模式发布

项目-->Build Android APK-->Sign package-->Create

填入密码，别名，勾选Use Keystore password，国家代码CN



用自己写的Activity需要把AndroidManifast.xml中的<activity 中的android:name=改为自己的实现的包名>



[Android按返回键（后退键）Back键事件捕获的两种方法](https://blog.51cto.com/u_15329836/3401290)



[【Android报错】java.io.IOException: Cleartext HTTP traffic to …not permitted完美解决](https://blog.csdn.net/weixin_43876206/article/details/103497419)





gradle 的 大坑

在projects里面生成 Create Templates。

**gradle版本**

android->gradle->wrapper->gradle-wrapper.properties里面修改gradle的版本。

jdk17不能用太低的gradle版本，目前用的是gradle-7.6-bin.zip

C:\Users\Akira\.gradle\wrapper\dists\ 查看已经下载的gradle版本。

**gradle插件版本**

android->build.gradle里面修改gradle插件版本。

gradle插件版本也有对应。目前用的是7.4.0

详细可以看https://developer.android.google.cn/build/releases/gradle-plugin?hl=zh-cn
