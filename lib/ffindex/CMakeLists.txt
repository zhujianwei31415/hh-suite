cmake_minimum_required(VERSION 2.8.12 FATAL_ERROR)
set(CHECK_MPI 1 CACHE BOOL "Check MPI availability")
SET(HAVE_MPI 1 CACHE BOOL "Have MPI")

project(ffindex C)
include_directories(src)
include_directories(src/ext)
add_subdirectory(src)

