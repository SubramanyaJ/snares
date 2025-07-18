cmake_minimum_required(VERSION 3.10)
project(snares C)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Wextra -Werror -O2")

set(SOURCES
    src/main.c
)

add_executable(snares ${SOURCES})
