# mywpay-sdk-android

1.项目根build.gradle中添加：

allprojects {
    repositories {
        jcenter()
        google()
        maven { url "https://raw.githubusercontent.com/Duanle/mywpay-sdk-android/master/" }
       ...
    }
}

2.项目build.gradle中添加依赖：

 implementation 'com.vito.wpay.opensdk:mywpay-sdk-android:version'
