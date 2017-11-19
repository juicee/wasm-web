cmake_minimum_required(VERSION 3.7)
project(testwasm)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(testwasm ${SOURCE_FILES})
include_directories('/Users/parkerzhu/Desktop/projects/emsdk-portable/emscripten/1.37.22/system/include')