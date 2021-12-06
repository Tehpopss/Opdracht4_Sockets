cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Opdracht4)

add_library(PJ_RPI PJ_RPI.c)
install (TARGETS PJ_RPI DESTINATION lib)
install (FILES PJ_RPI.h DESTINATION include)
link_libraries(PJ_RPI)

add_executable(Http https_server.c)


