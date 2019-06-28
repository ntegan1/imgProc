# Raspberry Pi Image Processing using OpenCV for autonomous navigation
### Python
* [OpenCV Dependencies and install](https://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/)
* [Pi Camera OpenCV](https://www.pyimagesearch.com/2015/03/30/accessing-the-raspberry-pi-camera-with-opencv-and-python/)
* [OpenCV 4.1.0 Docs](https://docs.opencv.org/4.1.0/)
### Non Python
* [linux install](https://docs.opencv.org/4.1.0/d7/d9f/tutorial_linux_install.html)
* [using with gcc,CMake](https://docs.opencv.org/4.1.0/db/df5/tutorial_linux_gcc_cmake.html)

### Installing Dependencies
##### dev tools
build-essential cmake pkg-config
##### image io packages
libpng12-dev -- is version 1.2, libpng16-16 is installled (v1.6 runtime).
So install libpng12-dev I guess although may be old

libjpeg-dev, libtiff5-dev, libjasper-dev
##### vid io packages
libavcodec-dev libavformat-dev libswscale-dev libv4l-dev

next, libxvidcore-dev libx264-dev
##### highgui
Displays images to screen, basic GUIs. Need libgtk2.0-dev
##### Optimization (matrix op)
libatlas-base-dev gfortran
##### Python bindings
python2.7-dev python3-dev

#### MAKE WITH
```
cmake -D CMAKE_BUILD_TYPE=RELEASE \
> -D CMAKE_INSTALL_PREFIX=/usr/local \
> -D INSTALL_PYTHON_EXAMPLES=ON \
> -D BUILD_EXAMPLES=ON ..
```

### Also look into
ROS, Mavlink, Ardupilot, Pixhawk
