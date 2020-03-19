# Hackintosh_AMD
设备信息：
- AMD Ryzen 5 2600 / AMD Ryzen 5 2700 
- B450M  
- RX580  
- bcm943602cs
- 芝奇 DDR4 3000HZ 32G
## DOC :
*** 

### 10.15.2安装方法：

[参照黑果小兵博客](https://blog.daliansky.net/)

[macOS Catalina 10.15.3 镜像](https://blog.daliansky.net/macOS-Catalina-10.15.3-19D76-Release-version-with-Clover-5103-original-image-Double-EFI-Version.html)

*** 

### 10.14.6安装方法：

[说明文档](https://vanilla.amd-osx.com/)

[视频说明](https://www.bilibili.com/video/av66328246?from=search&seid=5909070990651981103)

[蓝牙wifi驱动参考](https://post.smzdm.com/p/a83d937n/)

[驱动下载和文档](https://bitbucket.org/RehabMan/)

[macOS Mojave 10.14.6(18G87) Installer for Intel and AMD with Clover 5050 and WEPE.dmg](https://blog.daliansky.net/macOS-Mojave-10.14.6-18G87-Release-version-with-Clover-5033-original-image.html)
*** 

## TIP:
 1. 当配置安装U盘的时候，写镜像的软件可能会报错（1 device failed），无视继续重启进入安装即可，U盘需要8G以上的8G不够，最好使用好点的U盘速度快成功率会高一些
  
 2. 配置完安装U盘时候，最后一次安装系统（进入用户设置那次，语言等）偶尔会出现灰色屏幕，只有右上角有鼠标指针，重启重新操作一遍即可。
  
 3. 最好使用独立的硬盘安装。
 
 4. 所需要的文件都在，镜像也提供出来了

 5. 由于我使用的是pci-e的intel 9260无线网卡蓝牙模块，所以无线是不能驱动的，蓝牙驱动是可以驱动的，只不过需要先启动win然后重启才能识别蓝牙，稍微有点麻    烦，这个需要通过博通的蓝牙模块来彻底解决这个问题，
  
 ![image.png](https://i.loli.net/2019/10/06/HVyZz1XfDpT9q5B.png)
