cmake_minimum_required(VERSION 3.21)
project(MiniHttpServer)

set(CMAKE_CXX_STANDARD 14)

add_executable(MiniHttpServer HttpServer.c)
