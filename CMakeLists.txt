cmake_minimum_required(VERSION 4.0)
project(matrix_c C)

set(CMAKE_C_STANDARD 99)

add_library(matrix_c SHARED Matrix.c)
