cmake_minimum_required(VERSION 3.12)

include(pico_sdk_import.cmake)

project(pico_fun C CXX ASM)
set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 17)

set(PICO_FUN_PATH ${PROJECT_SOURCE_DIR})

pico_sdk_init()

add_subdirectory(blink)
add_subdirectory(hello_world)
add_subdirectory(st7735_test)
