cmake_minimum_required(VERSION 3.10)
project(geek_time_cpp)

add_subdirectory(01)
add_subdirectory(02)
add_subdirectory(03)
add_subdirectory(04)
add_subdirectory(05)
add_subdirectory(09)
add_subdirectory(10)
add_subdirectory(11)
add_subdirectory(16)
add_subdirectory(17)
add_subdirectory(18)
add_subdirectory(19)
add_subdirectory(20)
add_subdirectory(21)
add_subdirectory(22)
add_subdirectory(23)
add_subdirectory(24)
add_subdirectory(25)
add_subdirectory(26)
add_subdirectory(27)
if(CMAKE_CXX_COMPILER_ID MATCHES GNU)
  add_subdirectory(28)
  add_subdirectory(29)
elseif(MSVC)
  add_subdirectory(28)
  add_subdirectory(29)
endif()
add_subdirectory(30)
