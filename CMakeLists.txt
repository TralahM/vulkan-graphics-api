cmake_minimum_required(VERSION 3.10.2)
project (VulkanAPI)
set(VULKAN_INC /home/african/vulkan/1.2.135.0/x86_64/include)
include_directories(${VULKAN_INC})
add_executable(VulkanTest VulkanFunctions.cpp)
