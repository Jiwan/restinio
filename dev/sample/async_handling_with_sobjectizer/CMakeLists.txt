set(SAMPLE sample.async_handling_with_sobjectizer)
include(${CMAKE_SOURCE_DIR}/cmake/sample.cmake)
target_link_libraries(${SAMPLE} ${SOBJECTIZER_LIBS})
