# DynFileFS Debian Packaging

This repository contains the packaging files for building a Debian package of [DynFileFS](https://github.com/Tomas-M/dynfilefs), a FUSE filesystem for dynamically-enlarged files.

## About DynFileFS

DynFileFS is a FUSE-based utility that provides a dynamically-enlarged virtual file. All changes to the virtual file are stored in the specified storage file(s). It is useful for creating large files on demand, such as disk images.

## Building the Package

### Prerequisites
- Debian-based system
- Required build dependencies: `debhelper-compat (= 10)`, `libfuse-dev`

## Usage

### Build the package
To build the DynFileFS Debian package and run all necessary checks, use:
```bash
make
```

### Clean build artifacts
To remove build files and artifacts, use:
```bash
make clean
```

## DynFileFS Author
- Tomas Matejicek

For more information, see the [upstream project](https://github.com/Tomas-M/dynfilefs).
