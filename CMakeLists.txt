cmake_minimum_required(VERSION 3.3)
project(ipd15c CXX)
include(.ipd/cmake/CMakeLists.txt)

add_cxx_test_program(bst_map_unique_test
        test/bst_map_unique_test.cxx
        src/bst_map_unique.cxx)

add_cxx_test_program(bst_map_raw_test
        test/bst_map_raw_test.cxx
        src/bst_map_raw.cxx)

