## 签名命令示例
java -jar signapk.jar platform.x509.pem platform.pk8 unsigned.apk signed.apk
* signapk.jar是签名命令，所有厂商通用
* platform.x509.pem platform.pk8是签名文件，根据厂商不同要使用不同的文件
* unsigned.apk是签名前APK的完整路径
* signed.apk是签名后APK的完整路径
## 注意事项
* 需提前安装好JDK并配置环境变量
* 执行命令需要在和signapk.jar同一目录下
## 厂商列表
* byd-比亚迪
* hlt-合力泰
* lianbao-联宝
* wld-万利达
