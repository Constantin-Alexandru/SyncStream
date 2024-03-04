set(CMAKE_GENERATOR "MinGW Makefiles" CACHE INTERNAL "" FORCE)

cmake_minimum_required(VERSION "3.26.2")

project("SyncStream")
add_executable("SyncStream" "./src/main.cpp")