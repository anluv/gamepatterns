cmake_minimum_required(VERSION 3.16.0)
project(gamepatterns, VERSION 0.0.0)
set(CMAKE_CXX_STANDARD 20)
file(GLOB SOURCES "src/*.cpp")
add_executable(${PROJECT_NAME} ${SOURCES})
