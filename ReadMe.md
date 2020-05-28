### NetWorkDetection

Android 网络诊断、网络检测库  
基于[AndroidHttpCapture](https://github.com/JZ-Darkal/AndroidHttpCapture)改造，剔除了不需要的功能，更精简。  
效果如图所示:  

![](./network_detaction.jpg)

### Usage
#### Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

```java
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```

#### Step 2. Add the dependency

```java
dependencies {
    implementation 'com.github.EthanCo:NetWorkDetection:1.0.2'
}
```

感谢 [AndroidHttpCapture](https://github.com/JZ-Darkal/AndroidHttpCapture) | [LDNetDiagnoService](https://github.com/Lede-Inc/LDNetDiagnoService_Android)