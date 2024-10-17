cmake_minimum_required(VERSION 3.16)

project(BarberShopProbleme_Medecin LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(BarberShopProbleme_Medecin main.cpp)

include(GNUInstallDirs)
install(TARGETS BarberShopProbleme_Medecin
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
