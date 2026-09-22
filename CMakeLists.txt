cmake_minimum_required(VERSION 3.20)
project(oving_6 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(oving_6
    main.cpp
    position.cpp
    ianimal.h
    ipositionprovider.h
    position.h
)
