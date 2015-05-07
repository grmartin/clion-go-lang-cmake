cmake_minimum_required(VERSION 3.2)

set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_LIST_DIR}/)

project(TestApplication Go)

set(SOURCE_FILES
    src/main/go/main.go)

add_executable(TestApplication ${SOURCE_FILES})