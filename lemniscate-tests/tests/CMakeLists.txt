include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runLemniscateTests Test.cpp)

target_link_libraries(runLemniscateTests gtest gtest_main)
target_link_libraries(runLemniscateTests lemniscate)