cmake_minimum_required(VERSION 3.12)
project(JuanPabloLobato_Caso_Final_Integrador)

set(CMAKE_CXX_STANDARD 11)

include_directories(/ruta/a/json11)
include_directories(/ruta/a/jsonlib)

add_executable(JuanPabloLobato_Caso_Final_Integrador
        main.cpp
        Variant.cpp  # Asegúrate de que este sea el nombre correcto de tu archivo fuente de Variant
)

target_link_libraries(TuProyecto /ruta/a/json11/libjson11.a)

target_link_libraries(TuProyecto /ruta/a/jsonlib/libjsonlib.a)
