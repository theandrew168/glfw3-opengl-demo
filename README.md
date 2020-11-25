# glfw3-opengl-demo
Cross-platform OpenGL demo using GLFW3

## Dependencies
[GLFW3](https://www.glfw.org/) (zlib) - Multi-platform library for desktop OpenGL / Vulkan development

## Building
This project is built using POSIX-compatible [make](https://pubs.opengroup.org/onlinepubs/009695399/utilities/make.html).
For unix-like systems, it can be built natively.
For Windows builds, [mingw-w64](http://mingw-w64.org/doku.php) is used to cross-compile the project from a unix-like system.

### Linux (Native, Debian-based)
```
sudo apt install make libglfw3-dev
make
```

### macOS (Native)
```
brew install make glfw
make -f Makefile.macos
```

### Windows (Cross-Compile)
From Linux (Debian-based):
```
sudo apt install build-essential mingw-w64
make -f Makefile.mingw
```

From macOS:
```
brew install make mingw-w64
make -f Makefile.mingw
```
