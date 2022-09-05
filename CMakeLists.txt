cmake_minimum_required(VERSION 3.1)
project(extract_feature CXX)

find_package(OpenCV REQUIRED)

add_executable(a.out extract_feature/main.cpp)
