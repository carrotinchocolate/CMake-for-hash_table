cmake_minimum_required(VERSION 3.8)
project(hash_table)

# Use C++11 standard for compiling
set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES src/main.cpp src/hash_table.cpp)
set(HEADER_FILES include/hash_table.h)

add_executable(hash_table ${SOURCE_FILES} ${HEADER_FILES})