# embedded-python-cpp

A use case of embedding python into C++ applications/library has come up at work. The target C++ code is a library which gets called by a simulation engine. The library has functions that we wish to delegate to python scripts so that once the libraries are compiled, we can change the algorithms present in the python scripts (or swap in python scripts) such that the choice of algorithm for a specific functionality can be changed dynamically.

Here will be the protoype work before it is integrated into the system used at work.

