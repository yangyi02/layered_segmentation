# Layered Object Detection for Multi-Class Segmentation

## Introduction

This is a Matlab implementation of the layered object segmentation algorithm described in [1, 2]. The algorithm utilizes the object detection results obtained from deformable part-based models [3] with superpixels obtained from [4], and builds a Bayesian inference framework towards the semantic and instance segmentation of multi-class objects in PASCAL VOC dataset [5]. 

Acknowledgements: We graciously thank the authors of the previous code releases and image benchmarks for making them publically available.

## Using the code

1. Move to the `code_basic` directory
2. Start Matlab (version > 2013a).
3. Run `compile.m` to compile the helper functions. (You may also edit `compile.m` to use a different convolution routine depending on your system.)
4. Run `demo.m` to see the detection code run on sample images.
5. By default, the code is set to output the highest-scoring detection in an image.

## References

[1] Y. Yang, S. Hallman, D. Ramanan, C. Fowlkes. [Layered Object Detection for Multi-Class Segmentation](https://yangyi02.github.io/research/layers/index.html). CVPR 2010.

[2] Y. Yang, S. Hallman, D. Ramanan, C. Fowlkes. [Layered Object Models for Image Segmentation](https://yangyi02.github.io/research/layers/index.html). PAMI 2012.

[3] P. Felzenszwalb, R. Girshick, D. McAllester, D. Ramanan. [Discriminatively Trained Deformable Part Models](http://www.rossgirshick.info/latent/). PAMI 2010.

[4] P. Arbelaez, M. Maire, C. Fowlkes, J. Malik. [Contour Detection and Hierarchical Image Segmentation](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html). PAMI 2011.

[5] M. Everingham, L. Van Gool, J. Winn, A. Zisserman. [The PASCAL Visual Object Classes (VOC) Challenge](http://host.robots.ox.ac.uk/pascal/VOC/). IJCV 2010.

