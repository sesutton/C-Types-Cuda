# C-Types-Cuda

In order to convert cuda file to shared object run the following:

nvcc -Xcompiler -fPIC -shared -o cuda_sum.so cuda_sum.cu
