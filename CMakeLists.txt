cmake_minimum_required(VERSION 3.13)

set(TESS_PUBLIC_HEADERS_PATH ${CMAKE_CURRENT_SOURCE_DIR}/include)

include_directories(${TESS_PUBLIC_HEADERS_PATH})

install(FILES ${TESS_PUBLIC_HEADERS_PATH} DESTINATION "${CMAKE_INSTALL_PREFIX}/include")

add_subdirectory(src)