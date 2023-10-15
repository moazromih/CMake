cmake_minimum_required(VERSION 3.27.7)


project(WIFI_LIBRARY)


set(EXECUTABLES
    Lab3.cpp
)

add_subdirectory(${CMAKE_SOURCE_DIR}/lib)

message("Executables added ${EXECUTABLES}")

add_executable(wifi ${EXECUTABLES})


target_include_directories(wifi PUBLIC lib/)
target_link_libraries(wifi PUBLIC Wifi_Lib)
