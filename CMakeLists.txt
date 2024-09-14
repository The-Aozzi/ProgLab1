cmake_minimum_required(VERSION 3.10.0)

project(ProgLab1 VERSION 1.0.${PATCH_VERSION} LANGUAGES C CXX)

add_definitions(-D PATCH_VERSION=${PATCH_VERSION})

add_executable(ProgLab1 main.cpp)

