Go-Tensorflow based on JetsonNano
=================================
Overview:
---------------------------------
### 1. function: Using Tensorflow on JetsonNano with GO
### 2. environmet:Linux-arm
### 3. dependencies:bazel,cmake

1.Make JetsonNano System
---------------------------------
### Refer to the link:https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit
### 1.download developer kit
### 2.flash the system into SD card

2.Install GO
---------------------------------
### According your system to download the install package from [golang official webside](https://golang.org/)
   When you click the download item, it will jump to the next page and it shows you how to install golang.
   For example:install linux-amd64 GO referring to this link:https://golang.org/doc/install?download=go1.11.11.linux-amd64.tar.gz

3.GOCV Install
---------------------------------
### Refer to the link:https://gocv.io/
***NOTICE***:For the slow download speed of opencv4.1 and opencv_contrib4.1, I submit the package to the server to accelerate the download speed.
             The build file needs to be modified accordingly.

4.GO-Tensorflow compile
--------------------------------
### Step1:Download and Install BAZEL  
#### Bazel download and install reference [webside](https://docs.bazel.build/versions/master/install-compile-source.html)
***NOTICE***: Refer to this [website](https://www.tensorflow.org/install/source) to comfirm to install which version of BAZEL according to tenforflow version.
### Step2:Compile tensorflow from source file
#### Refer to this [webside](https://devtalk.nvidia.com/default/topic/1055131/jetson-agx-xavier/building-tensorflow-1-13-on-jetson-xavier/) to set configurtion,build tensorflow and set environment path.May be it will take at least 6 hours to build.

Conclusion
=================================
It must take version of each package into consideration!! If you choose the wrong version, it will not work and occur many errors!