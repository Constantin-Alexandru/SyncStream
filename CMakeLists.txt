set(CMAKE_GENERATOR "MinGW Makefiles" CACHE INTERNAL "" FORCE)

cmake_minimum_required(VERSION "3.26.2")

add_subdirectory("./ANSI-Library")

project(SyncStream)
add_executable(SyncStream "./src/main.cpp")

target_link_libraries(SyncStream PRIVATE ANSI-Library)