cmake_minimum_required(VERSION 3.15...4.0)
project(pdqsort VERSION 1.0 LANGUAGES CXX)

add_library(pdqsort pdqsort.h)
target_compile_features(pdqsort PUBLIC cxx_std_11)
