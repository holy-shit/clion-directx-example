cmake_minimum_required(VERSION 3.12)
project(src)

set(CMAKE_CXX_STANDARD 17)

add_executable(src main.cpp)

set(LIBS d3d9 d3d11 d3dcompiler_43)
target_link_libraries(src ${LIBS})
