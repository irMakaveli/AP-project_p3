project(project)
set(CMAKE_CXX_STANDARD 11)
cmake_minimum_required(VERSION 3.0)
include_directories(include /)
add_executable(app 
 src/ap-project-p1.cpp
 src/animal.cpp 
 src/hen.cpp 
 src/feed.cpp 
 src/money.cpp 
 src/buy.cpp 
 src/cow.cpp 
 src/sheep.cpp
 )