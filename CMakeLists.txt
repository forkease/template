cmake_minimum_required( VERSION 3.28...3.28 )
project( m20odule VERSION 0.0.0 LANGUAGES CXX )

set( M20PROJ m20__${PROJECT_NAME} )

add_subdirectory( source )
add_library( m20::${PROJECT_NAME} ALIAS ${M20PROJ} )
