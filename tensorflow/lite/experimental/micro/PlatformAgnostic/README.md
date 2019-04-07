This directory contains hardware platform-agnostic code. Do remember that the debug_log.cc code must be changed to a specific hardware implementation (e.g. through serial console). 

Some points to consider:
1. Your cross-compiler must be compatible with C++11. 
2. When building, issue the following command: "make CC=[YOUR C CROSS COMPILER] CXX=[YOUR C++ CROSS COMPILER]"
"make clean"
