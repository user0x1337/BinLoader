cmake_minimum_required(VERSION 3.22)
project(BinaryLoader)
set(CMAKE_CXX_FLAGS  "-lbfd -rdynamic")
set(CMAKE_CXX_STANDARD 23)

add_executable(BinaryLoader inc/loader.h inc/loader.cpp binLoader.cpp)
