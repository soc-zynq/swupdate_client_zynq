# Create a library called "swupdate_client_zynq"
add_library(swupdate_client_zynq_lib swupdate_client_zynq.cpp)

# Specify include directories for the library
target_include_directories(swupdate_client_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
