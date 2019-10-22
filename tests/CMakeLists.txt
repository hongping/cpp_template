# ------------------------------------------------------------------------------
# SECTION: add unit tests
# ------------------------------------------------------------------------------
add_executable(runUnitTests
  doa.cpp
)

target_link_libraries(runUnitTests gtest gtest_main)

add_test(gtestAlive runUnitTests)