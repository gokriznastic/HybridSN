# Implementation of Hybrid-Spectral-Net for Hyperspectral Image Classification.

<br/>
## Model

<img src="figure/HSI-RN.png"/>

Fig: Proposed HybridSpectralNet (HybridSN) Model with 3D and 2D convolutions for hyperspectral image (HSI) classification.

## Prerequisites

- [Anaconda 2.7](https://www.anaconda.com/download/#linux)
- [Tensorflow 1.3](https://github.com/tensorflow/tensorflow/tree/r1.3)
- [Keras 2.0](https://github.com/fchollet/keras)

## Results

### Indian Pines (IP) dataset

<img src="figure/IP-FC.jpg"/> <img src="figure/IP-GT.jpg"/> <img src="figure/IP-Pr.jpg"/>

Fig.4  The IN dataset classification result (Overall Accuracy 99.86%) of SSRN using 30% samples for training. (a) False color image. (b) Ground truth labels. (c) Classification map. 

### University of Pavia (UP) dataset

<img src="figure/UP.png"/>

Fig.5  The UP dataset classification result (Overall Accuracy 99.98%) of SSRN using 30% samples for training. (a) False color image. (b) Ground truth labels. (c) Classification map.

### Salinas (SA) dataset

<img src="figure/SA.png"/>

Fig.5  The UP dataset classification result (Overall Accuracy 100%) of SSRN using 30% samples for training. (a) False color image. (b) Ground truth labels. (c) Classification map.

## Acknowledgement

Part of codes is from a implementation of Classification of HSI using CNN by [Konstantinos Fokeas](https://github.com/KonstantinosF/Classification-of-Hyperspectral-Image).
