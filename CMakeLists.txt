cmake_minimum_required(VERSION 3.28)
project(Queue01)

set(CMAKE_CXX_STANDARD 17)

add_executable(Queue01 main.cpp
        Queue.cpp
        Queue.h)
