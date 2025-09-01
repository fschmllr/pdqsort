cmake_minimum_required(VERSION 3.15...4.0)
project(pdqsort VERSION 1.0 LANGUAGES CXX)

add_library(pdqsort INTERFACE pdqsort.h)
target_compile_features(pdqsort INTERFACE cxx_std_11)
target_include_directories(pdqsort INTERFACE .)
