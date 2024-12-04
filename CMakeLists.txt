cmake_minimum_required(VERSION 3.24)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(
    Concurrency
    VERSION 0.1.0
    LANGUAGES C CXX
)

add_executable(
    main
    main.cpp
)
