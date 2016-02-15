cmake_minimum_required(VERSION 2.8)
project(base_cpp_cmake)

file (GLOB SRC src/*.cpp)

include_directories (include)

add_executable(base_cpp_cmake ${SRC})
