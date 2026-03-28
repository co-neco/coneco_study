cmake_minimum_required(VERSION 3.20)

project(cmake_study)

message(PROJECT_SOURCE_DIR)

set(local_test ON)
set(VERSION "1.0")
set(CACHE_VERSION "1.1" CACHE "STRING" "cache variable test ")
message(STATUS "VERSION = ${VERSION}")
message(STATUS "local_test = ${local_test}")
message(STATUS "CACHE_VERSION = ${CACHE_VERSION}")