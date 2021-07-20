include_directories(/home/hfut/TestCMAKE/usr/include/hello)
link_directories(/home/hfut/TestCMAKE/usr/lib)
add_executable(main main.c)
target_link_libraries(main hello)
#CMAKE_INCLUDE_PATH
#CMAKE_LIBRARY_PATH
#FIND_PATH(myHeader hello.h)
#IF(myHeader)
#INCLUDE_DIRECTORIES(${myHeader})
#ENDIF(myHeader)

#FIND_LIBRARY
