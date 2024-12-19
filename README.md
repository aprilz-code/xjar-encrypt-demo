# xjar-encrypt-demo

使用ProGuard + Xjar对jar文件进行加密，防止反编译

### 可直接在windows运行的jar文件

out\artifacts\xjarencrype_jar\xjarencrype.jar
此文件包含简单的用户界面，可以选择要加密的jar，保存路径，输入密码，然后点击开始进行加密。<br><br>
运行之前请确认已有java环境

#### 附Xjar源码地址

https://github.com/core-lib/xjar

https://blog.csdn.net/qq_37320062/article/details/129305658

<injar>${project.build.finalName}.jar</injar> 改成本地jar也行，然后配置加密
