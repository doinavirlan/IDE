cmake_minimum_required(VERSION 2.8)

project(cprogram)

add_executable(main main.c)

install(TARGETS main DESTINATION bin)
