cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

cmake_policy(SET CMP0079 NEW)

add_compile_definitions(ENABLE_ASSERTS)

project(fractal C CXX ASM)

# set(CMAKE_WIN32_EXECUTABLE TRUE)
set(CMAKE_C_STANDARD 99)
SET(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_MESSAGE_LOG_LEVEL WARNING)

find_package(Vulkan REQUIRED)

add_subdirectory(fractal)
add_subdirectory(packages)
add_subdirectory(test)

enable_testing()