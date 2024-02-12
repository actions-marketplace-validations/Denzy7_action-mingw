# action-mingw
Build with modern MinGW on Windows (x86_64 only (currently)). Powered by [winlibs](https://winlibs.com). Prefarably use with CMake  

While it's possible to just use ubuntu to build, Windows is better since we don't have to deal with a toolchain file when using CMake. Append `-G MinGW Makefiles` to your cmake command
