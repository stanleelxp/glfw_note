cmake_minimum_required(VERSION 3.0)

project(splitview)

add_executable(splitview splitview.c glad.c)

set(INCLUDE_DIR /usr/local/include ./)
set(LINK_DIR /usr/local/lib)
set(LINK_LIST libglfw.so libdl.so libm.so)

include_directories(${INCLUDE_DIR})
link_directories(${LINK_DIR})
target_link_libraries(splitview ${LINK_DIR}/${LINK_LIST})

