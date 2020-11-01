cmake_minimum_required(VERSION 3.12)

project(Example VERSION 0.1 DESCRIPTION "An example")

add_subdirectory(lib)
add_subdirectory(bin)                    
                      
include(CTest)
enable_testing(MAKE_DIRECTORY test)
add_subdirectory(test)