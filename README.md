# F860
这是一个安卓开发

1. 分别创建文件夹 Android_SDK 和 AndroidStudio 用来放置SDK与软件
2. SDK选API30
3. 更改gradle-wrapper.properties
`distributionUrl=https\://mirrors.cloud.tencent.com/gradle/gradle-8.0-bin.zip`
4. 更改settings.gradle.kts（Maven镜像）
```
maven { url=uri ("https://www.jitpack.io")}
maven { url=uri ("https://maven.aliyun.com/repository/releases")}
maven { url=uri ("https://maven.aliyun.com/repository/google")}
maven { url=uri ("https://maven.aliyun.com/repository/central")}
maven { url=uri ("https://maven.aliyun.com/repository/gradle-plugin")}
maven { url=uri ("https://maven.aliyun.com/repository/public")}
```
5. 更改local.properties（SDK位置）
`sdk.dir=D\:\\Android\\Android_SDK`
