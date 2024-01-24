# New Simple X11 Window GUI in C

This project demonstrates the creation of a basic X11 window GUI using C programming. It serves as a hands-on practice for those learning C.

## X11 Development Dependencies (Debian/Ubuntu Packages)

To build and run the X11 window GUI project, make sure you have the following dependencies installed on your Debian/Ubuntu system or WSL:

- `libx11-dev`: This package provides the development files necessary for building applications that use the X11 library.

- `libx11-doc`: Install this package for access to documentation related to the Xlib libraries. While not strictly required for compilation, it contains valuable information about Xlib functions, data types, and programming practices, making it a useful reference for developers.

## Getting Started:

Follow these steps to set up and run the project:

### 1. Install Dependencies:

Ensure that the required dependencies (`libx11-dev` and `libx11-doc`) are installed on your system using your package manager.
```bash
sudo apt-get install libx11-dev libx11-doc
```

### 2. Build and Compile:

Use your preferred compiler to build the project. For example, with `gcc`:
```bash
gcc your_project.c -o your_project -lX11
```

### 3. Run the Program:
```bash
./project_name.out
```