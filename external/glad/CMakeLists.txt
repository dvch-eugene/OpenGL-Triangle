cmake_minimum_required(VERSION 3.21 FATAL_ERROR)

project(Glad)

add_library(glad STATIC include/glad/glad.h src/glad.c)
target_include_directories(glad PUBLIC include/)

