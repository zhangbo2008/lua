
cmake_minimum_required(VERSION 3.9)
project(lua C)
 


set(CMAKE_C_STANDARD 99)
#代码中的目录名，我这里是test.c，这里应该根据你代码文件名改变而改变
set(SOURCE_FILES lapi.c)
 
add_executable(lua ${SOURCE_FILES})

