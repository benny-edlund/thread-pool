cmake_minimum_required( VERSION 3.16.3 )

project(bs_thread_pool)
add_executable( bs_thread_pool_test BS_thread_pool_test.cpp )
target_link_libraries(bs_thread_pool_test pthread)
