cmake_minimum_required(VERSION 3.19.1)
project(NET_LINUX_V1.0)
include_directories(./inc)
aux_source_directory(./src DIR_SRC)
aux_source_directory(./demo DIR_DEMO)
#add_subdirectory(./src)

add_executable(Demo ${DIR_DEMO} ${DIR_SRC} )