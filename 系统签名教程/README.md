## 签名命令示例
java -jar signapk.jar platform.x509.pem platform.pk8 unsigned.apk signed.apk
* signapk.jar是签名命令，所有厂商通用
* platform.x509.pem platform.pk8是签名文件，根据厂商不同要使用不同的文件
* unsigned.apk是签名前APK的完整路径
* signed.apk是签名后APK的完整路径
## 注意事项
* 执行命令需要在和signapk.jar同一目录下
