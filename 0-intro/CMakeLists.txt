cmake_minimum_required(VERSION 3.25)
project(cpl-coding C)

set(CMAKE_C_STANDARD 17)

# gcc hello.c -o hello
add_executable(hello hello.c)
add_executable(guess guess.c)