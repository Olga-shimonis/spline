cmake_minimum_required(VERSION 3.23)
project(spline_project C)

set(CMAKE_C_STANDARD 99)

add_executable(spline_project main.c determination.c determination.h)
