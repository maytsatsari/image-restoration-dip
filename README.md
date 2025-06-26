# Image Restoration & Analysis – DIP Assignment

This repository contains the solution to the mid-semester assignment for the course **Digital Image Processing** at the University of Ioannina.

The project focuses on applying spatial and frequency domain techniques for restoring distorted grayscale images, alongside answering theoretical questions related to image enhancement and filtering.

---

##  Assignment Overview

The assignment is divided into two parts:

###  Part 1: Image Restoration with Python
- Implemented in Jupyter Notebook (`assignment.ipynb`)
- Covers 7 distorted grayscale images of `lena.png`
- Techniques applied include:
  - Histogram Equalization
  - Histogram Specification
  - Gaussian Filtering
  - Median Filtering (manual NumPy implementation)
  - Log & Power Transformations
  - Unsharp Masking
  - Sharpening with custom convolution kernels
- Quality metrics computed:
  - MSE (Mean Squared Error)
  - PSNR (Peak Signal-to-Noise Ratio)
  - SSIM (Structural Similarity Index)

###  Part 2: Theoretical Analysis
- Includes answers to:
  - Why histogram equalization is not always flat
  - Effect of smoothing vs. Laplacian order
  - Isotropy of Laplacian operator
  - Convolution theorem (proof)



---

##  Technologies & Tools

- Python 3.7+
- Jupyter Notebook / Google Colab
- NumPy, SciPy, Matplotlib, OpenCV
- Skimage for evaluation metrics

---

##  Files

```
.
├── assignment.ipynb   # Python implementation in notebook form
├── images/            # Folder with input distorted and target images (not included)
```

> The `images/` folder mentioned in the notebook includes files like:
> - lena.png (reference)
> - distorted_img_1.png … distorted_img_7.png (inputs)

---

##  Author

This assignment was completed **individually** by _Maria Tsatsari_ 
---
