cmake_minimum_required (VERSION 2.8.3)
project (image)
find_package(OpenCV)
add_executable(image image.cpp)
target_link_libraries(image ${OpenCV_LIBS})
add_executable(test test.cpp)
