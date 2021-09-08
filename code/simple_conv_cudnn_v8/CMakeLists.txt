cmake_minimum_required(VERSION 3.18)

project(simpleConv CUDA)

# Automatically finds the OpenCV package
find_package(OpenCV REQUIRED)

# Link libraries of cuda and cudnn
link_libraries(cudnn "/anaconda/lib/")
link_libraries(cudart "/usr/lib64/")

set(CMAKE_CUDA_STANDARD 14)

add_executable(simpleConv main.cu)

set_target_properties(
        simpleConv
        PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)

target_link_libraries(simpleConv ${OpenCV_LIBS})


