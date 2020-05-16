# QPyTorch
[![Downloads](https://pepy.tech/badge/qtorch)](https://pepy.tech/project/qtorch) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

QPyTorch is a low-precision arithmetic simulation package in
PyTorch. It is designed to support researches on low-precision machine
learning, especially for researches in low-precision training. 

## Installation

requirements:

- Python >= 3.6
- PyTorch >= 1.0
- GCC >= 4.9 on linux

Install other requirements by:
```bash
pip install -r requirements.txt
```

Install QPyTorch through pip:
```bash
pip install qtorch
```

For more details about compiler requirements, 
please refer to [PyTorch extension tutorial](https://pytorch.org/tutorials/advanced/cpp_extension.html).

## Examples
- Low-Precision ResNets using FP9 on ImageNet
Traing ResNet-50
```bash
python3 examples/resnet50.py -a resnet50 --pretrained --start-epoch=90 --epochs=95 /path_to_imagenet
```
.. image:: https://drive.google.com/open?id=1JxHAmkbBthQ36fr2jdAi8krkwJ9Q6rtL :alt: Retraining Process

## Team
* [Tianyi Zhang](https://scholar.google.com/citations?user=OI0HSa0AAAAJ&hl=en)
* Zhiqiu Lin
* [Guandao Yang](http://www.guandaoyang.com/)
* [Christopher De Sa](http://www.cs.cornell.edu/~cdesa/)
