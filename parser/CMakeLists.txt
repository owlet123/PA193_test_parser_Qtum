add_library(parser-lib STATIC
        parser.cpp
        parser.h)

target_include_directories(parser-lib INTERFACE
        ${CMAKE_CURRENT_SOURCE_DIR}/..
        )

set_target_properties(parser-lib PROPERTIES
        LINKER_LANGUAGE CXX
        )