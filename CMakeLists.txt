# PROJECT(lzham)
cmake_minimum_required(VERSION 2.8)
option(BUILD_X64 "build 64-bit" ON)
option(BUILD_SHARED_LIBS "build shared/static libs" ON)

add_subdirectory(lzhamdecomp)
add_subdirectory(lzhamcomp)
add_subdirectory(lzhamdll)
