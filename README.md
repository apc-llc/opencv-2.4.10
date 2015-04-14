### OpenCV: Open Source Computer Vision Library

[![Gittip](http://img.shields.io/gittip/OpenCV.png)](https://www.gittip.com/OpenCV/)

#### Building with CUDA & OpenCL support

```
$ git clone https://github.com/apc-llc/opencv-2.4.10.git
$ cd opencv-2.4.10
$ mkdir build
$ cd build/
$ cmake -DHAVE_CUDA=TRUE -DHAVE_OPENCL=TRUE -DCMAKE_INSTALL_PREFIX=$(pwd)/../install ..
$ make -j12
$ make install
```

#### Resources

* Homepage: <http://opencv.org>
* Docs: <http://docs.opencv.org>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <http://code.opencv.org>

#### Contributing

Please read before starting work on a pull request: <http://code.opencv.org/projects/opencv/wiki/How_to_contribute>

Summary of guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the coding style guide.
