include_directories(${PROJECT_SOURCE_DIR}/systems/metal_common)
add_library(metal_common stack.c delay.c stubs.c)
