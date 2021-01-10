add_library(cppTracing Source/cppTracing.cpp Source/cppTracing.hpp)

target_compile_features(cppTracing PUBLIC cxx_std_20)