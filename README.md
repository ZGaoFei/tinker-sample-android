# tinker-sample-android
tinker test

注意运行时：
使用官方example中设置的配置

选择tinker-sample-android下面的tasks下面的build里面的assemble***来打原始包

选择tinker-sample-android下面的tasks下面的tinker里面的tinkerPatch***来打Patch包


> 注意

修改相关的内容为你项目对应的内容

1、application="项目对应的路径+名字"

2、AndroidManifest.xml中的application的name="项目的application"

3、build.gradle中修改loader="项目的BaseBuildInfo"

> 打补丁包的流程

1、正常流程安装APP

2、出现bug，并修改代码

3、选择一个apk为参考点，打差异包

4、运行tinkerPatch来打Patch包

> 注意

  选择上次打的apk为参考apk，修改build.gradle中的
  
  tinkerOldApkPath、tinkerApplyMappingPath、tinkerApplyResourcePath
  
  对应的版本名称
  
  参考包的位置为app\build\bakApk文件夹下，包含apk和R.txt
  
  生成的Patch包的位置为app\build\outputs\tinkerPatch文件夹下对应的patch_signed_7zip.apk
  
