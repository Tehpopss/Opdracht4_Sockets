cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Opdracht4)

link_libraries(libtlpi.a)

add_executable(Http https_server.c)


