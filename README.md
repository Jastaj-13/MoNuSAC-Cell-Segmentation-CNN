# MoNuSAC-Cell-Segmentation-CNN

##  Overview
Developed a U-Net based deep learning pipeline to segment and classify four cell types (Epithelial, Lymphocyte, Macrophage, Neutrophil) using H&E stained histological images.

## Challenges & Solutions
- **Class Imbalance:** Solved via stochastic data augmentation (flips/rotations).
- **Resolution Variance:** Standardized inputs to 256x256 using Albumentations.
- **Staining Diversity:** Integrated Batch Normalization to handle contrast shifts.

## Performance
- **Peak F1 Score:** 0.4449
- **Training:** 50 Epochs on Tesla T4 GPU.
- **Inference:** Optimized for CPU deployment.

## Try it out
[https://colab.research.google.com/drive/1Yh1sBdhkJsmJ4N06hWHsGtslDwOi_S6z?usp=sharing]

