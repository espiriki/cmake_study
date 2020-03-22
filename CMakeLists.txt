cmake_minimum_required(VERSION 3.17)

set(CMAKE_SYSTEM_PROCESSOR arm)
set(CMAKE_SYSTEM_NAME Generic)

set(CMAKE_EXE_LINKER_FLAGS "--specs=nosys.specs")

set(CMAKE_C_COMPILER "D:/SysGCC/9.2.1/SysGCC/bin/arm-none-eabi-gcc.exe")
set(CMAKE_CXX_COMPILER "D:/SysGCC/9.2.1/SysGCC/bin/arm-none-eabi-g++.exe")

project(foo)

add_executable(foo.elf foo.cpp)