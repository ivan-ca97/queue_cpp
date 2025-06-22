cmake_minimum_required(VERSION 3.15)
project(queue LANGUAGES CXX)

add_library(queue INTERFACE)

target_include_directories(queue INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/includes
)