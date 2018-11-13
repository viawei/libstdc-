# libstdc-
Xcode10移除了libstdc库，不得不使用时需要拷贝的文件

1、将 iPhoneOS 文件中内容复制到路径1：
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/

2、将 iPhoneSimulator 文件中内容复制到路径2：
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib/

3、将 simruntime 文件中内容复制到路径3：
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/


