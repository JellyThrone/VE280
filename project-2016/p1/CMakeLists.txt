CMAKE_MINIMUM_REQUIRED(VERSION 3.5)
project(p1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

SET(SOURCE_FILES answer/p1.cpp)

add_executable(p1 ${SOURCE_FILES})

