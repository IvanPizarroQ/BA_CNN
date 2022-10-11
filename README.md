# An Attention-Based Architecture for Hierarchical Classification with CNNs

This directory contains an implementation of BA-CNN paper (link). In our experiments, we used CIFAR-10,CIFAR-100 and Fashion MNIST, and compared our proposed method (BA-CNN) results with B-CNN (Zhu and Bain, 2017), H-CNN (Zhang,2021), Add-net and Concat-net (Inoue,2020)


## Requirements
For the experiments, CIFAR-10 and Fashion MNIST were imported from keras library. CIFAR-100 can be downloaded from https://www.cs.toronto.edu/~kriz/cifar.html


# Files
 - BA_CNN_CIFAR_10.ipynb: Models B-CNN, H-CNN, Add-net, Concat-net and BA-CNN Base B and C, running on CIFAR-10 dataset.
 - BA_CNN_CIFAR_100.ipynb: Models B-CNN, H-CNN, Add-net, Concat-net and BA-CNN Base C, running on CIFAR-100 dataset.
 - BA_CNN_CIFAR_FASHION_MNIST.ipynb: Models B-CNN, H-CNN, Add-net, Concat-net and BA-CNN Base C, running on Fashion MNIST dataset.




# References

[B-CNN](https://arxiv.org/abs/1709.09890)

```
@article{zhu2017b,
  title={B-CNN: branch convolutional neural network for hierarchical classification}, 
  author={Zhu, Xinqi and Bain, Michael},
  journal={arXiv preprint arXiv:1709.09890},
  year={2017}
}
```
Sample code on https://github.com/zhuxinqimac/B-CNN

[H-CNN](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cvi2.12023)
```
@article{zhang2021hierarchical,
  title={Hierarchical bilinear convolutional neural network for image classification},
  author={Zhang, Xiang and Tang, Lei and Luo, Hangzai and Zhong, Sheng and Guan, Ziyu and Chen, Long and Zhao, Chao and Peng, Jinye and Fan, Jianping},
  journal={IET Computer Vision},
  volume={15},
  number={3},
  pages={197--207},
  year={2021},
  publisher={Wiley Online Library}
}
```
Sample code not available

[B-CNN applied to Fashion MNIST](https://www.sciencedirect.com/science/article/abs/pii/S0957417418305992)
```
@article{seo2019hierarchical,
  title={Hierarchical convolutional neural networks for fashion image classification},
  author={Seo, Yian and Shin, Kyung-shik},
  journal={Expert systems with applications},
  volume={116},
  pages={328--339},
  year={2019},
  publisher={Elsevier}
}
```
Sample code on https://github.com/AdicherlaVenkataSai/HCNN

[Add-net and Concat-net](https://ieeexplore.ieee.org/abstract/document/9207246)
```
@inproceedings{inoue2020semantic,
  title={Semantic Hierarchy-based Convolutional Neural Networks for Image Classification},
  author={Inoue, Matheus and Forster, Carlos Henrique and dos Santos, Antonio Carlos},
  booktitle={2020 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2020},
  organization={IEEE}
}
```
Sample code not available
