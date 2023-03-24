cmake_minimum_required(VERSION 3.23.2)

project(single_linked_list)

add_executable(single_linked_list single-linked-list/main.cpp single-linked-list/single-linked-list.h)

target_link_libraries(single_linked_list)