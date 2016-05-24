# stitcher

This is a sample stitcher fetched from opencv/samples.
It can be used as generating the panorama by different images.

'cmake . && make'
'./stitcher Univ_images/#.jpg'

Before the cmake, you have to make sure the opencv and its contirb(extra modules) installed.

'''
$ git clone https://github.com/Itseez/opencv.git
$ git clone https://github.com/Itseez/opencv_contrib.git
$ cd opencv
$ mkdir build
$ cd build
$ cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -DOPENCV_EXTRA_MODULES_PATH=<path_to_contrib>/modules ..
$ make
$ sudo make install
'''


