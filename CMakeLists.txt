cmake_minimum_required(VERSION 3.10.2)
project (VulkanAPI)
include_directories($VULKAN_SDK/include)
add_executable(VulkanTest VulkanFunctions.cpp)
