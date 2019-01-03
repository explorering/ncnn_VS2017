基于ncnn搭建的VS2017工程，用于调试。
1、编译安装protobuf；可以按照ncnn官网上安装；
2、CMAKE生成VS工程。参考第三部，直接用CMAKE生成VS工程，注意选项64位；
   https://blog.csdn.net/CosmosHua/article/details/81543844
   
点击 Add Entry：Protobuf_LIBRARIES=D:\protobuf-3.4.0\Builds\install\lib\libprotobuf.lib
点击 Add Entry：Protobuf_INCLUDE_DIR=D:\protobuf-3.4.0\Builds\install\include 
点击 Add Entry：Protobuf_PROTOC_EXECUTABLE=D:\protobuf-3.4.0\Builds\install\install/bin/protoc.exe 
修改（可选）：CMAKE_CONFIGURATION_TYPES=Release 
修改：Protobuf_SRC_ROOT_FOLDER=D:/protobuf-3.4.0/src 

3、配置opencv 64位；

4、添加相关demo 就可以调试了；

   
