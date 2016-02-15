cmake_minimum_required(VERSION 2.8)
project(unydiff)

file (GLOB SRC src/*.cpp)

include_directories (include)

add_executable(unydiff ${SRC})
