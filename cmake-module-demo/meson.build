project('cmake-module-demo', 'c')

cmake = import('cmake')

# Add a CMake subproject
cmake_subproject = cmake.subproject('foo')

# Use a target from the CMake subproject
cmake_target = cmake_subproject.target('foo')

executable('cmake-module', 'main.c', link_with: cmake_target)