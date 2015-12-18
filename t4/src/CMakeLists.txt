PROJECT(NEWHELLO)

SET(CMAKE_INCLUDE_DIRECTORIES_BEFORE, on)
INCLUDE_DIRECTORIES(/Users/moses/iboxpay/cmake/t3/install/include/hello)
LINK_DIRECTORIES(/Users/moses/iboxpay/cmake/t3/install/lib)

ADD_EXECUTABLE(main main.c)

TARGET_LINK_LIBRARIES(main libhello.a)
