# VFN
Pytorch Implementation of **Volumetric Fusion Net** for volumetric segmentation of medical images. The key idea is that we first train three 2D networks from different views of CT scans (axial, sagittal and coronal), and then fuse the predictions with a relatively shallow and fast network (*VFN*).

[Bridging the Gap Between 2D and 3D Organ Segmentation with Volumetric Fusion Net](https://arxiv.org/abs/1804.00392)  
Yingda Xia<sup>1</sup>, Lingxi Xie<sup>1</sup>, Fengze Liu<sup>1</sup>, Zhuotun Zhu<sup>1</sup>, Elliot K. Fishman<sup>2</sup>, Alan L. Yuille<sup>1</sup>  
<sup>1</sup>Johns Hopkins University, <sup>2</sup>Johns Hopkins Medical Institue  
In MICCAI 2018

## Results on NIH pancreas dataset
![table](figures/table.png)

## Qualitative Analysis
![figure](figures/figure.png)
