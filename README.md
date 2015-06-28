# OSBuild - FOR ANDROID DEVELOPERS

![icon.png](/Other/icon.png)

Ever wanted to peek inside and know more about your device? Well, **OSBuild**, a simple, lightweight, clean and beautiful app, meets your needs. And it works on all phones running Android 2.2 and above!

A simple UI and some nice features make it great tool especially for Android developers and learners.

### Features
* List **RICH RAW** info about the device with keeping most programming words.
* Provide **RICH** related data, like `19  KITKAT  2013-10  39.2%  19`.
* List all features the system supported, such as `FEATURE_USB_HOST`.
* **READ WIFI PASSWORDS**. (**If ROOTED**)
* **OPEN SOURCE**. You can see its source codes on [GitHub](https://github.com/by-syk/OSBuild) to get useful code sections.

### Modules
* Build (`MODEL`, etc.)
* Display (`densityDpi`, etc.)
* Telephony (`deviceId`, etc.)
* CPU (`cpuinfo_max_freq`, etc.)
* Memory (`volumePaths`, etc.)
* Package (`systemAvailableFeatures`, etc.)
* Sensor (`sensorList`, etc.)
* SuperSu
etc.

### Example
There is a slice of data which OSBuild got from my Android phone:
```
android.app.ActivityManager.
   getDeviceConfigurationInfo().
      reqGlEsVersion: 0x00030000  3.0
   getMemoryClass(): 128  128.00MB
   getLargeMemoryClass(): 512  512.00MB
   MemoryInfo.
      threshold: 100663296  96.00MB
      totalMem: 1940213760  1.81GB
android.os.Environment.
   getRootDirectory(): /system/
      Total Size: 660058112  629.48MB
      Available Size: 142319616  135.73MB  21%
   getDataDirectory(): /data/
      Total Size: 13394399232  12.47GB
      Available Size: 1620070400  1.51GB  12%
   getExternalStorageState(): mounted  MEDIA_MOUNTED
   isExternalStorageRemovable(): false
   getExternalStorageDirectory(): /storage/emulated/0/
      Total Size: 13341970432  12.43GB
      Available Size: 1567641600  1.46GB  11%
android.os.storage.StorageManager.
   getVolumePaths().
      /storage/emulated/0/  true
      /storage/usbotg/  false
```

### Donate
Not financially.

Just **Share the Page** to me by E-mail. As you can see, only some hardware info about the device (**NO PRIVACY**).

I'm making the effort to finish my project, DAD (Database of Android Devices). If OSBuild helps a lot, please help me a bit. Thank you.

### Besides...
Meet a new device and want to figure its info out? Install **OSBuild** and **Share the Page**. OK, you've got it.

Salute to [Sony Xperia AppXplore](http://developer.sonymobile.com/knowledge-base/tools/download-appxplore-and-learn-more-about-your-apps/).

### History Versions
[OSBuild_v1.1.0(150606).apk](/Other/OSBuild_v1.1.0(150606).apk)

[OSBuild_v1.1.4(150610).apk](/Other/OSBuild_v1.1.4(150610).apk)

[OSBuild_v1.2.0(150628).apk](/Other/OSBuild_v1.2.0(150628).apk)

### Screenshots
![screenshot1.png](/Other/screenshot1.png)

![screenshot2.png](/Other/screenshot2.png)

![screenshot3.png](/Other/screenshot3.png)
