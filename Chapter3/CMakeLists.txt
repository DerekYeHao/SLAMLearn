#声明要求的 cmake版本
cmake_minimum_required(VERSION 2.8)

#声明一个工程
project(Eigen)

#添加头文件
include_directories("/usr/local/Cellar/eigen/3.3.4/include/eigen3")

#添加一个可执行程序
add_executable(helloEigen eigenMatrix.cpp)

