# Bazel Scala Example

This is an example project that demonstrates how to build a Scala project with Bazel.

## Prerequisites

- [Bazel](https://bazel.build)

## XCode Setup

```bash
bazel run //:xcodeproj
```

This will generate an XCode project file in the source tree that is configured to build the project with Bazel.

## Build

```bash
bazel build //...
```

# Run

```bash
bazel run //HelloWorldSwift
```