cmake_minimum_required(VERSION 3.19)
project(TinySTL_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(test)

add_executable(TinySTL_master
        test/test.h
        test/test_alloc.h
        test/test_list.h
        test/test_vector.h
        alloc.h
        allocator.h
        construct.h
        deque.h
        heap.h
        iterator.h
        list.h
        main.cpp
        memory.h
        priority_queue.h
        queue.h
        set.h
        stack.h
        tree.h
        type_traits.h
        uninitialized.h
        vector.h)
