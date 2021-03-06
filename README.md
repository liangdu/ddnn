# Distributed Deep Neural Networks over the Cloud, the Edge and End Devices
    
We propose distributed deep neural networks (DDNNs) over distributed computing hierarchies, consisting of the cloud, the edge (fog) and end devices. While being able to accommodate inference of a deep neural network (DNN) in the cloud, a DDNN also allows fast and localized inference using shallow portions of the neural network at the edge and end devices. Due to its distributed nature, DDNNs enhance data privacy and system fault tolerance for DNN applications. When supported by a scalable distributed computing hierarchy, a DDNN can scale up in neural network size and scale out in geographical span. In implementing a DDNN, we map sections of a DNN onto a distributed computing hierarchy. By jointly training these sections, we minimize communication and resource usage for devices and maximize usefulness of extracted features which are utilized in the cloud. As a proof of concept, we show a DDNN can exploit geographical diversity of sensors to improve recognition accuracy and reduce communication cost. In our experiment, compared with the traditional method of offloading raw sensor data to be processed in the cloud, DDNN locally processes most sensor data on end devices and is able to reduce the communication cost by a factor of over 20x.

## Dependencies

This library is dependent on Python 2.7+ and [Chainer](http://chainer.org/). Please install Chainer 1.17+ before starting.

```
pip install chainer
```

## Quick Start

## Paper

Our paper is available [here]()

If you use this model or codebase, please cite:
```bibtex
@article{teerapittayanondistributed,
  title={Distributed Deep Neural Networks over the Cloud, the Edge and End Devices},
  author={Teerapittayanon, Surat and McDanel, Bradley and Kung, HT},
  jornal={Proceedings of the 37th IEEE International Conference on Distributed Computing Systems},
  year={2017}
}
```

## License
  
Copyright (c) 2017 Bradley McDanel, Surat Teerapittayanon, HT Kung, Harvard University

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.  
