cmake_minimum_required(VERSION 2.8)
project( gaussian )
find_package( OpenCV REQUIRED )
add_executable( SmoothbyGaussian.cpp )
target_link_libraries( gaussian ${OpenCV_LIBS} )
