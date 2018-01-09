# AutoPackage
AutoPackage script
自动打包脚本是基于github开源的一个脚本根据自己项目修改成的。
Jenkins打包遇到的一些坑
1.appliable not device?
一种情况是可以使用rvm use system 添加到脚本中，如果没效果的话请使用xcode9.0以上的xcode的xcodebuild 打包，我尝试了 xcode7.3 xcode8.2都不能解决这个问题
2.把schma文件属性设置成shared
3.记得把权限打开，因为安装jenkins会创建jenkins用户，如果你不用jenkins用户的话会有权限问题
4.证书问题最好是把login.keychain复制到jenkins/libliary下
5.多尝试别灰心，尽管jenkins有很多坑包括xcode版本mac系统版本 插件版本 项目设置属性 等等.......
