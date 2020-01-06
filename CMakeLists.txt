cmake_minimum_required(VERSION 3.14)
project(rsa_library)

#add_library(rsa_library rsa.h rsa.c test.c)
#set(CMAKE_C_FLAGS "-std=c99")
#set(CMAKE_C_FLAGS "${CMAKE_ENABLE_C99}")
set(CMAKE_C_STANDARD 99)
add_executable(rsa_library rsa.h rsa.c test.c)