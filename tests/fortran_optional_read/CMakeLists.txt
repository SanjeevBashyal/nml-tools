cmake_minimum_required(VERSION 3.20)
project(optional_generated_read LANGUAGES Fortran)

set(CMAKE_Fortran_STANDARD 2008)
set(CMAKE_Fortran_STANDARD_REQUIRED ON)

add_executable(optional_generated_read
  conformance.f90
  out/nml_helper.f90
  out/nml_optional.f90
  out/nml_required.f90
)
