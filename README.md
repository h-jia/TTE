## TinyTTA Engine

TinyTTA Engine is a lightweight framework for enabling Test-Time Adaptation (TTA) on edge devices like microcontrollers (MCUs). Built upon TFLM, it features:

- On-device backpropagation with floating-point computation
- Support for common DNN operators (ReLU, FullyConnected, Softmax, Maxpool, Avgpool, Conv, DepthwiseConv)
- Memory-efficient layer-wise update strategy with dynamic allocation
- Automatic differentiation for backward graph construction
- Graph optimization through operation fusion and quantization

The framework is specifically designed to operate within the resource constraints of edge devices while enabling model adaptation capabilities.

If you have any questions please email at hong.jia@unimelb.edu.au and ydk21@cam.ac.uk

If you find this code useful for your research, please consider citing the following papers:

```
@article{jia2024tinytta,
  title={TinyTTA: Efficient Test-time Adaptation via Early-exit Ensembles on Edge Devices},
  author={Jia, Hong and Kwon, Young and Orsino, Alessio and Dang, Ting and Talia, Domenico and Mascolo, Cecilia},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={43274--43299},
  year={2024}
}
```
