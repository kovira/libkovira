cmake_minimum_required (VERSION 2.8)
project (libkovira)

set (OUTPUT "kovira")
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

include_directories (
	include
)

add_library (${OUTPUT} SHARED
	##
)
