cmake_minimum_required(VERSION 3.10)
project(Shapes)

set(SOURCE_FILES main.cpp triangle.cpp triangle.h tetragon.cpp tetragon.h equilateral.cpp equilateral.h isosceles.cpp isosceles.h parallelogram.cpp parallelogram.h print.cpp print.h rectangle.cpp rectangle.h rhombus.cpp rhombus.h right_tr.cpp right_tr.h shape.cpp shape.h square.cpp square.h)
add_executable(Shapes ${SOURCE_FILES})