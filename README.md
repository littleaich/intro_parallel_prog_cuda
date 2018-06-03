#### Introduction to Parallel Programming with CUDA

* Individual files can be compiled with nvcc as follows:

```
nvcc -o <EXECUTABLE_NAME> <FILE_NAME.EXTENSION>
nvcc -o cube\_integer cube\_integer.cu
```

* Problem set 2 change in the list of opencv libraries
```
make CXXFLAGS="-std=c++11"
```
