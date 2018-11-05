cmake_minimum_required(VERSION 3.0.0)

set(CMAKE_C_FLAGS "-O3 -Wall")

include_directories(include)

file(GLOB SOURCES "src/*.c")

add_executable(nesasm ${SOURCES})

install(TARGETS nesasm DESTINATION bin)
