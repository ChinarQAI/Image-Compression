# CQAI_PCA

# Image Compression using PCA

## Overview

This project demonstrates image compression using Principal Component Analysis (PCA) for dimensionality reduction. By reducing the dimensionality of image data, we can compress images effectively while retaining most of the important features, thus optimizing storage space without significantly compromising image quality.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Image compression is crucial for efficient storage and transmission of images in various applications. PCA is a statistical technique that transforms data into a set of orthogonal components, capturing the most significant variance in the data. This project applies PCA to compress images by reducing their dimensionality.

## Features

- Compress grayscale and color images using PCA
- Adjustable number of principal components for compression level control
- Visual comparison between original and reconstructed images
- Batch processing of multiple images

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- scikit-learn
- Pillow (PIL)
- opencv-python
- setuptools

  #### You can install the above requirements using the requirements.txt file, Just have to execute the below command:
  ```bash
  pip install -r requirements.txt
  

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
