################################################################################
# epmalloc cmake configuration file                                            #
################################################################################
cmake_minimum_required(VERSION 3.15.5)
project(epmalloc C)
add_executable(epmalloc main.c)
set_property(TARGET epmalloc PROPERTY CMAKE_C_EXTENSIONS OFF)
set_property(TARGET epmalloc PROPERTY CMAKE_C_STANDARD 90)