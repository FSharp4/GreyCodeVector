cmake_minimum_required(VERSION 3.29)
project(GrayCodeVector)

set(CMAKE_CXX_STANDARD 20)

include_directories(.)

add_executable(GrayCodeVector
    generator.cpp
    generator.h)
