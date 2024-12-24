cmake_minimum_required(VERSION 3.10)
project(uint128_t)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(uint128_t STATIC ${CMAKE_CURRENT_SOURCE_DIR}/uint128_t.cpp)