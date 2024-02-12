# action-mingw
Build with MinGW on Windows. Powered by [winlibs](https://winlibs.com). Loosely based on [setup-mingw](https://github.com/egor-tensin/setup-mingw). Prefarably use with CMake

While it's possible to just use ubuntu to build, Windows is better since we don't have to deal with a toolchain file when using CMake. Append `-G MinGW Makefiles` to your cmake command
