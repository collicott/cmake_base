This is an extremely simple example C++ application which uses CMake. 
It will build and install an application called CMakeHelloWorld which simply outputs "Hello, world!" to stdout.  

### Installation ###
As this is an example of how to use CMake you'll need to download it (http://www.cmake.org/cmake/resources/software.html) or install it via:
```bash
sudo apt-get install cmake
```
Once CMake has been install navigate to the root of the project and issue the following commands:
```bash
mkdir build
cd build
cmake .. && make
```


### Usage ###
Once the executable has been created simply call `CMakeHelloWorld`, either from the build directory or anywhere (if you installed to /usr/local/bin by also running make install but this is not necessary, etc).


