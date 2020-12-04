# Custom builds for Tensorflow (pip wheels)

These work for builds using an old LGA775 cpu and a modern GPU

march=Core2 -> SSE2, SSE3
- Works for all Core2 processors

march=Core2 -msse4.1 -> SSE2, SSE3, SSE4.1
- Works for all [Socket P/Wolfdale/Yorkfield](https://en.wikipedia.org/wiki/Penryn_(microarchitecture)) processors (Core 2 Q8xxx and above)

|OS|[TensorFlow](https://github.com/tensorflow/tensorflow)|[Python](https://www.python.org/downloads/)|[CUDA](https://developer.nvidia.com/cuda-toolkit-archive)|[cuDNN](https://developer.nvidia.com/cuDNN)|[Compute Capability](https://en.wikipedia.org/wiki/CUDA#GPUs_supported)|Optimization|Link|
|:---|:---|:---|:---|:---|:---|:---|:---|
|Ubuntu 20.04|2.3.1|3.8|10.2|7.6.5|6.1|SSE2, SSE3|[placeholder]()|
|Ubuntu 20.04|2.3.1|3.8|10.2|7.6.5|6.1|SSE2, SSE3, SSE4.1|[placeholder]()|
