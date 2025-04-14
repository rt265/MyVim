cmake_minimum_required(VERSION 3.10)

project(MyVim VERSION 1.0.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)

add_compile_options(-Wall -Wextra -pedantic -Werror)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pipe -std=c++20")

add_executable(MyVim main.cpp)
