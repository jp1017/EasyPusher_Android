# EasyPusher_Android
A simple, robust, low latency RTSP video&audio&screen stream pusher and recorder on android.精炼、稳定、高效的安卓前/后摄像头/手机桌面屏幕采集、编码、RTSP直播推送工具，充分秉承了RTP在即时通信领域中的技术特点，延时控制在300ms~500ms；

EasyPusher是EasyDarwin流媒体团队开发的一个推送流媒体音/视频流给开源流媒体服务器EasyDarwin的标准RTSP/RTP协议推送库，全平台支持(包括Windows/Linux(32 & 64)，ARM各平台，Android、IOS)，通过EasyPusher我们就可以避免接触到稍显复杂的RTSP/RTP/RTCP推送流程，只需要调用EasyPusher的几个API接口，就能轻松、稳定地把流媒体音视频数据推送给RTSP流媒体服务器进行转发和分发，EasyPusher经过长时间的企业用户检验，稳定性非常高;

## 分支说明 ##
- master分支是EasyPusher APP(https://fir.im/EasyPusher)的工程。如果需要验证Pusher的功能，可以使用这个工程进行编译运行，AS的版本无要求。
- library分支是EasyPusher library的工程，主要面向开发者，将pusher功能集成到现有APP的场景。library使用了android architecture component的一些特性，非常便于集成。（见：https://developer.android.com/topic/libraries/architecture/index.html）。该分支要求AS版本3.0-beta7及以上。

## 版本下载 ##

- Android [https://fir.im/EasyPusher ](https://fir.im/EasyPusher "EasyPusher_Android")

![EasyPusher_Android](http://www.easydarwin.org/skin/bs/images/app/EasyPusher_AN.png)

- iOS [https://itunes.apple.com/us/app/easypusher/id1211967057](https://itunes.apple.com/us/app/easypusher/id1211967057 "EasyPusher_iOS")

![EasyPusher_iOS](http://www.easydarwin.org/skin/bs/images/app/EasyPusher_iOS.png)

## 版本更新记录 ##
### v1.0.17.0218 (Build 10) ###
1. 支持本地录像，边推边录；

### 1.1.16.1127 (Build 6) ###
1. 优化推送速度；
1. 增加软件编码；
1. 国内镜像：http://fir.im/EasyPusher；

### 1.0.16.1007 (Build 5) ###
1. 增加屏幕录制、直播；
1. 增加升级功能；

### 1.0.16.0423 (Build 3) ###
1. 支持基本的安卓Android前/后置摄像头RTSP直播推送；
1. 支持采集安卓Android手机麦克风声音直播；

## 获取更多信息 ##

邮件：[support@easydarwin.org](mailto:support@easydarwin.org) 

WEB：[www.EasyDarwin.org](http://www.easydarwin.org)

QQ交流群：[465901074](http://jq.qq.com/?_wv=1027&k=2G045mo "EasyPusher & EasyRTSPClient")

Copyright &copy; EasyDarwin.org 2012-2017

![EasyDarwin](http://www.easydarwin.org/skin/easydarwin/images/wx_qrcode.jpg)
