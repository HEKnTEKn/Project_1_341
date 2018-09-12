cmake_minimum_required(VERSION 3.12)
project(Project_1_341)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Project_1_341
        fall-2017.csv
        main.cpp
        spring-2018.csv)
