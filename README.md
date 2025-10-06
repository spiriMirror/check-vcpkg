# check-vcpkg

A template for fast spiriMirror vcpkg check.

If you are creating a package, please using this template to test your package.

## vcpkg Integration

The project is configured with:
- Default vcpkg official registry (https://github.com/microsoft/vcpkg)
- spiriMirror organization registry (https://github.com/spiriMirror/vcpkg)

To add dependencies, edit `vcpkg.json` and add packages to the `dependencies` array.
