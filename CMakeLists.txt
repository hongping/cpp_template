cmake_minimum_required (VERSION 3.15)
project(CPP_TEMPLATE)

# ------------------------------------------------------------------------------
# SECTION: Google Test (gtest) unit testing framework
# ------------------------------------------------------------------------------
add_subdirectory(external/googletest-release-1.10.0 EXCLUDE_FROM_ALL)

# Prevent overriding the parent project's compiler/linker settings on Windows
set(gtest_force_shared_crt ON CACHE BOOL "" FORCE)

enable_testing()

# ------------------------------------------------------------------------------
# SECTION: add unit tests
# ------------------------------------------------------------------------------
add_subdirectory(tests)