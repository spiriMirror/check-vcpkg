# check-vcpkg
A template for fast spiriMirror vcpkg check.

## Overview
This template provides a starting point for C++ projects using vcpkg package manager. It includes:

- **vcpkg.json**: Manifest file for vcpkg dependencies
- **vcpkg-configuration.json**: Configuration with default official vcpkg registry and spiriMirror organization registry
- **main.cpp**: Simple hello world C++ program
- **CMakeLists.txt**: CMake build configuration

## Building the Project

```bash
# Configure with CMake
mkdir build && cd build
cmake ..

# Build
cmake --build .

# Run
./check-vcpkg
```

## vcpkg Integration

The project is configured with:
- Default vcpkg official registry (https://github.com/microsoft/vcpkg)
- spiriMirror organization registry (https://github.com/spiriMirror/vcpkg-registry)

To add dependencies, edit `vcpkg.json` and add packages to the `dependencies` array.
