cmake_minimum_required(VERSION 3.2)
project(RC5_Experiments)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(RC5_Experiments ${SOURCE_FILES})