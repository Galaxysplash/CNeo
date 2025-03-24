cmake_minimum_required(VERSION 3.30)
project(CNeo)

include_directories(src)
include_directories(src/classes)

set(CMAKE_CXX_STANDARD 20)

add_library(CNeo STATIC src/Core.cpp src/Core.h
        src/classes/base.cpp
        src/classes/base.h
        src/Keywords.cpp
        src/Keywords.h)
