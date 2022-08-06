file(GLOB cppfiles ${PROJECT_SOURCE_DIR}/src/*.cpp)

add_library(ymfm STATIC ${cppfiles})

target_include_directories(ymfm PUBLIC "${PROJECT_SOURCE_DIR}/src")
