cmake_minimum_required(VERSION 3.26)
project(untitled21 C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled21 main.c)

add_library(str tasks/string_.c
        tasks/string_.h
)

target_link_libraries(untitled21 str)