gocl
====

Go Open Compute Language (GOCL) - Go OpenCL Binding


Library documentation: http://www.khronos.org/registry/cl/sdk/1.2/docs/man/xhtml/

In order to build this, make sure you have the required drivers and SDK installed for your graphics card. 

You will need at least and opencl.lib.

For NVIDIA, these are included in the CUDA SDK: https://developer.nvidia.com/opencl

ATI should include them with their APP SDK: http://developer.amd.com/resources/heterogeneous-computing/opencl-zone/tools-and-libraries/

The locations of the library and include file can be supplied by way of environment variables: 

export CGO_LDFLAGS=-L$AMDAPPSDKROOT/lib/x86_64
export CGO_CFLAGS=-I$AMDAPPSDKROOT/include
