cmake_minimum_required(VERSION 4.0)
project(Graph)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Graph_test
        main.cpp
        Graph.cpp
)
