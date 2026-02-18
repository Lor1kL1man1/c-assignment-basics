cmake_minimum_required(VERSION 3.20)
project(C_Basics_Assignment C)

set(CMAKE_C_STANDARD 11)

add_executable(datatypes src/01_datatypes.c)
add_executable(operators src/02_operators.c)
add_executable(conditionals src/03_conditionals.c)
add_executable(loops src/04_loops.c)
add_executable(cmd src/05_command_line.c)
add_executable(magic src/06_magic_numbers.c)
