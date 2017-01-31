##eyeLike: Eyeball tracker

[![https://www.youtube.com/watch?v=aGmGyFLQAFM](https://img.youtube.com/vi/aGmGyFLQAFM/0.jpg)](https://www.youtube.com/watch?v=aGmGyFLQAFM)

##Building

CMake is required to build eyeLike.

###OSX or Linux with Make
```bash
# do things in the build directory so that we don't clog up the main directory
mkdir build
cd build
cmake ../
make
./bin/eyeLike # the executable file
```

###On OSX with XCode
```bash
mkdir build
./cmakeBuild.sh
```
then open the XCode project in the build folder and run from there.

###On Windows
There is some way to use CMake on Windows but I am not familiar with it.

##Blog Article:
- [Using Fabian Timm's Algorithm](http://thume.ca/projects/2012/11/04/simple-accurate-eye-center-tracking-in-opencv/)
