cmake_minimum_required(VERSION 3.16)

project(HelloWorld)
enable_testing()

add_executable(hello main.c)
add_test(hello hello)
