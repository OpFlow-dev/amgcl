cmake_minimum_required(VERSION 3.5)
project(amgcl_smoke LANGUAGES CXX)

add_executable(amgcl_smoke main.cpp)
target_include_directories(amgcl_smoke PRIVATE "$ENV{PREFIX}/include")
set_target_properties(amgcl_smoke PROPERTIES CXX_STANDARD 11 CXX_STANDARD_REQUIRED YES)
