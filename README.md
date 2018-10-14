# tensorflow 32 Bit on Linux
A 32-bit version of tensorflow.  
I have noticed that tensorflow doesn't provide a version for i686 platform.So I followed [this instruction](https://stackoverflow.com/a/41561561/7812435) and built tensorflow by myself.  
It took me about 6 hours to build one on an old computer(with AMD Athlon II X4 635 @ 2.9GHz and 4G RAM).The package has been tested on Linux Mint 18.3.   
A compatible problem happened when building bazel.Have a look at [my issue](https://github.com/bazelbuild/bazel/issues/5394#issuecomment-397778800) may be helpful to you.  
If you met any problems,[propose issues](https://github.com/w568w/tensorflow-32-bit-for-linux/issues/new) please.  
# Download
A built python package,tensorflow-1.9.0rc0-cp27-cp27mu-linux\_i686.whl has been uploaded to this repository.