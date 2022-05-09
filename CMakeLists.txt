cmake_minimum_required(VERSION 3.10)

project(cppgen)

add_executable(cppgen Generator/lib/cppgen/CppGen.cpp)
add_subdirectory(Generator/packages/cpp-linenoise)


