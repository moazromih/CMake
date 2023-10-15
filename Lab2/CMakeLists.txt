cmake_minimum_required(VERSION 3.27.7)

set(EXECUTABLES
    Lab2.cpp
    ./src/sum.cpp
)
message("Executables added ${EXECUTABLES}")
project(SUM)

add_executable(sum ${EXECUTABLES})

include_directories(sum ./include)
