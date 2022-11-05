# Bazel examples to build C++ code

This package will showcase how to build C++ code in stages.
See [docs](https://bazel.build/start/cpp) for detail.

### Before you get started

Install Bazel by [Bazelisk](https://bazel.build/install/bazelisk).

### Stage 1
The first stage is really simple and shows you how to compile a binary with a single source file.

### Stage 2
The second stage will showcase how to build an application with multiple source and header files, separated in a library and a binary.

### Stage 3
The third stage showcases how to link multiple build directories by building multiple libraries in different packages and then connecting it up with the main application.

## Integrate with CLion

1. Install [Bazel Official Plugin](https://plugins.jetbrains.com/plugin/9554-bazel)
2. _File > Import Bazel Project..._ on CLion's GUI to start wizard
3. Select workspace where placed `WORKSPACE` file
4. Select BUILD file from _Generate from BUILD file_ to generate a project file

## Further helpful information

- [Drake: CLion IDE setup](https://drake.mit.edu/clion.html)
