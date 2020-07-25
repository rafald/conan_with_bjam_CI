![C/C++ CI](https://github.com/rafald/conan_with_bjam_CI/workflows/C/C++%20CI/badge.svg)

![C/C++ CI cmake](https://github.com/rafald/conan_with_bjam_CI/workflows/C/C++%20CI%20cmake/badge.svg)

# Github continuous integration (via github actions) of C++ project using conan package manager with bjam builder

*  Conan is prerequisite, b2 is downloaded by conan during build process.

*  Although bjam (b2 executable) is builder, the build process is controlled by conan because it does download b2 and calls it to build the targets.
 
* uses Catch library and huge folly library with many dependecies
