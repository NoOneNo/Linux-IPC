cmake_minimum_required(VERSION 3.14)
project(linux_api)

set(CMAKE_CXX_STANDARD 14)

add_executable(linux_api main.cpp pipe.cpp pipe.h chardev.cpp chardev.h socket.cpp socket.h)