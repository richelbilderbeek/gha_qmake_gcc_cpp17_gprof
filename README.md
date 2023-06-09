# gha_qmake_gcc_cpp17_gprof

Branch   |[![GitHub Actions logo](pics/GitHubActions.png)](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gprof/actions)
---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`master` |[![Check build](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gprof/actions/workflows/check_build.yml/badge.svg?branch=master)](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gprof/actions/workflows/check_build.yml)
`develop`|[![Check build](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gprof/actions/workflows/check_build.yml/badge.svg?branch=develop)](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gprof/actions/workflows/check_build.yml)

The goal of this project is to have a clean GitHub Actions build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++17`
 * Libraries: `STL` only
 * Code coverage: none
 * Profiling: `gprof`
 * Source: one single file, `main.cpp`

More complex builds:
 * [none]

Equally complex builds:

 * Use Travis CI (instead of GitHub Actions): [travis_qmake_gcc_cpp17_gprof](https://github.com/richelbilderbeek/travis_qmake_gcc_cpp17_gprof)
 * Use CMake (instead of `qmake`): [gha_cmake_gcc_cpp17_gprof](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_gprof)

Less complex builds:
 * [none]
 