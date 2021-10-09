cmake_minimum_required(VERSION 3.12)
project(cpp_lab1)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_EXE_LINKER_FLAGS  "-static-libstdc++")

add_executable(${PROJECT_NAME} main.cpp)
