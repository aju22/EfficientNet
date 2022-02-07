# EfficientNet

Introduced by Tan et al. in EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks, EfficientNet is a convolutional neural network architecture and scaling method that uniformly scales all dimensions of depth/width/resolution using a compound coefficient. Unlike conventional practice that arbitrary scales these factors, the EfficientNet scaling method uniformly scales network width, depth, and resolution with a set of fixed scaling coefficients.

EfficientNets also transfer well and achieve state-of-the-art accuracy on CIFAR-100 (91.7%), Flowers (98.8%), and 3 other transfer learning datasets, with an order of magnitude fewer parameters.

Find research paper : [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/abs/1905.11946)

![](https://raw.githubusercontent.com/tensorflow/tpu/master/models/official/efficientnet/g3doc/params.png)

This notebook is an attempt to understand the model architecture, intuition behind EFficientNet, and its implementation on a code-level in Tensorflow-Keras. (Includes all versions of EfficientNet : b0-b7)

This notebook also includes the additional Squeeze Excitation layer module, discussed in the paper and the Inverted Residual Blocks both used for building the entirety of EfficientNet.

