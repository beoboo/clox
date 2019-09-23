cmake_minimum_required(VERSION 3.0)

project(clox)

file(GLOB SRC_FILES *.c)

add_executable(${PROJECT_NAME} ${SRC_FILES})