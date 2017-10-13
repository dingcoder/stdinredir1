cmake_minimum_required(VERSION 3.8)
project(stdinredir1)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(stdinredir1 ${SOURCE_FILES})