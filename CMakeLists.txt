cmake_minimum_required(VERSION 3.28)
project(vulkan_example)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 23)

# 查找 Vulkan 包
find_package(Vulkan REQUIRED)

# 添加子目录
add_subdirectory(create_instance)
