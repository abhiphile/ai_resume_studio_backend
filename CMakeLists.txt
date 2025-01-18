cmake_minimum_required(VERSION 3.10)
project(resume_studio_backend VERSION 1.0)
set(CMAKE_CXX_STANDARD 17)

include_directories(${CMAKE_SOURCE_DIR}/lib/Crow/include)
include_directories(${CMAKE_SOURCE_DIR}/lib/libpqxx/include)
include_directories(${CMAKE_SOURCE_DIR}/lib/redis-cpp/include)

add_executable(resume_studio_backend src/main.cpp)
