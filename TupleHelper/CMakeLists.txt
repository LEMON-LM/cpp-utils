cmake_minimum_required(VERSION 2.8)

project(tuple_helper)

set(OUTPUTNAME tuple_helper)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -g -O2 -std=c++14")

aux_source_directory(. DIR_SRCS)
add_executable(${OUTPUTNAME} ${DIR_SRCS})

