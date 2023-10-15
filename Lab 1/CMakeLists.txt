cmake_minimum_required(VERSION 3.27.7)
project("Hello World" VERSION 1.0)
message("path is ${CMAKE_SOURCE_DIR}")
add_executable(HelloWorld HelloWorld.c)