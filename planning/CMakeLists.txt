cmake_minimum_required(VERSION 2.8.3)
project(ipp_planning)

find_package(catkin_simple REQUIRED)
catkin_simple(ALL_DEPS_REQUIRED)

##########
# EXPORT #
##########
cs_install()
cs_export()
