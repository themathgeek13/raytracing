cmake_minimum_required(VERSION 3.13)
project(raytracing)

set(CMAKE_CXX_STANDARD  14)

add_executable(raytracer raytracer.cpp vec3.h ray.h color.h hittable.h sphere.h hittable_list.h rtweekend.h)