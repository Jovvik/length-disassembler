cmake_minimum_required(VERSION 3.20)
project(length-disassembler)

set(CMAKE_CXX_STANDARD 23)

add_library(length-disassembler INTERFACE)
target_include_directories(length-disassembler PUBLIC Dependencies/length-disassembler/headerOnly)
