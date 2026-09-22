cmake_minimum_required(VERSION 3.10)
project(lab)

file(GLOB SOURCE_FILES *.c *.cc)

# Add test executable
add_executable(mylab.out ${SOURCE_FILES})

