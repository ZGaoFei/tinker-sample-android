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

// 目前就知道这些