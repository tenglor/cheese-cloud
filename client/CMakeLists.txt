cmake_minimum_required(VERSION 3.20.0 FATAL_ERROR)

project(cheese-cloud-client)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(cheese-cloud-client src/main.cpp)

