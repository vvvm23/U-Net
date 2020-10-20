# U-Net: Convolutional Networks for Image Segmentation

Implemention of the paper [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597) in PyTorch.

Currently just generates segmentation masks for MNIST. No mixing of images yet.

Diverges from the paper with regard to cropping feature maps. I pad the image instead the corresponding feature maps in the contracting and expanding paths are of matching dimension.
