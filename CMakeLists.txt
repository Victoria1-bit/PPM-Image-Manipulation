cmake_minimum_required(VERSION 3.21)
project(ImageProject)

set(CMAKE_CXX_STANDARD 17)

add_executable(ImageProject
        main.cpp
        Image.cpp
        Button.cpp
)

find_package(SFML 3 COMPONENTS System Window Graphics REQUIRED)

target_link_libraries(ImageProject PRIVATE
        SFML::System
        SFML::Window
        SFML::Graphics
)