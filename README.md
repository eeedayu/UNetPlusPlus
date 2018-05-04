# Nested Neural Networks for Medical Image Segmentation

This is an implementation of Nest-Net in Python and powered by the Keras deep learning framework (Tensorflow as backend).

## Nested U-Net Family

### Benchmarks

- Original U-Net ([Ronneberger, 2015](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28))
- ConvNet with bottleneck unit
- ResNet with residual unit
- DenseNet with dense unit

## Nested FCN Family

using the following backbone network architectures:

- VGG-16 ([Simonyan, 2014](https://arxiv.org/abs/1409.1556))
- ResNet-101 ([He, 2016](https://arxiv.org/abs/1512.03385))

Additional backbone architectures may be easily implemented.

## License

Detectron is released under the [MIT]().

## Citing Nest-Net

If you use Nest-Net in your research, please use the following BibTeX entry.

```
@inproceedings{zhou2018nestnet,
  title={Nested Neural Networks for Medical Image Segmentation},
  author={Zongwei Zhou, Md Mahfuzur Rahman Siddiquee and Jianming Liang},
  booktitle={International Conference on Medical Imaging with Deep Learning (MIDL)},
  year={2018}
}
```