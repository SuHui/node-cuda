# node-cuda

[node-cuda](https://github.com/kashif/node-cuda) provides [NVIDIA CUDA](http://developer.nvidia.com/category/zone/cuda-zone)™ bindings for [Node.js](http://nodejs.org/).

# 要求(Prerequisites)

You will need to have a CUDA compatible GPU as well as the latest [CUDA Drivers and Toolkit](http://developer.nvidia.com/cuda-downloads) installed for your platform. Currently only tested on Max OS X and Linux 64-bit.

# 安装(Installation)

To obtain and build the bindings: 

    git clone git://github.com/kashif/node-cuda.git
    cd node-cuda
    node-waf configure build

or install it via [npm](http://npmjs.org/):

    npm install node-cuda