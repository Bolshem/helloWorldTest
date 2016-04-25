cmake_minimum_required(VERSION 2.8)
project(helloWorldTest)

add_executable(helloWorldTest helloWorldTest.cpp)
#target_link_libraries(projectionSample realsense GL glfw)

install(TARGETS helloWorldTest DESTINATION ~/)
