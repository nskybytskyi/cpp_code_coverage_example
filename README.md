# Overview

This repository is an example of setting up code coverage for C++ projects. 

It uses `gcov` to generate coverage reports and `lcov` to visualize them. 

Integrations with [CMake](CMakeLists.txt) and [GitHub Actions](.github/workflows/coverage.yml) automate report generation. 

Finally, the reports are uploaded to report hosting provider [Coveralls](https://coveralls.io/).

This work is based on an [excellent step-by-step tutorial](https://www.danielsieger.com/blog/2022/03/06/code-coverage-for-cpp.html) by Daniel Sieger.

I dedicate this work to [public domain](LICENSE) with no restrictions whatsoever.

[![Coverage Status](https://coveralls.io/repos/github/nskybytskyi/cpp_code_coverage_example/badge.svg?branch=main)](https://coveralls.io/github/nskybytskyi/cpp_code_coverage_example?branch=main)