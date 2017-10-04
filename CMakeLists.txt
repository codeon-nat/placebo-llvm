cmake_minimum_required(VERSION 3.0)

project( placebo-llvm)

add_executable( lldb
main.c)

install( TARGETS lldb DESTINATION "bin")

