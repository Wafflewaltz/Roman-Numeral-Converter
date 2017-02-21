cmake_minimum_required(VERSION 3.6)
project(Roman_Numeral_Converter)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp RomanDecimalNumber.cpp RomanDecimalNumber.h)
add_executable(Roman_Numeral_Converter ${SOURCE_FILES})