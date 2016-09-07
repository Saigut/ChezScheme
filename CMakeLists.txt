project(ChezScheme C)
cmake_minimum_required(VERSION 2.8)

include_directories(
        ti3le/c
        ti3le/boot/ti3le
        ti3le/zlib
)

aux_source_directory(ti3le/c SRCS)