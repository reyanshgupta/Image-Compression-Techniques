# Image Compression Techniques: K-Means, DCT, Hadamard

This repository contains Python code for image compression using various techniques: K-Means clustering, Discrete Cosine Transform (DCT), and Hadamard Transform. These techniques can be used to reduce the file size of images while preserving their visual quality. This README provides an overview of the code and how to use it.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Results](#results)
- [License](#license)

## Introduction

Image compression is the process of reducing the file size of an image while trying to maintain its visual quality. This code repository demonstrates three different techniques for image compression:

1. **K-Means Compression**: This technique uses K-Means clustering to group similar colors in the image and replace them with cluster centroids.

2. **DCT Compression**: Discrete Cosine Transform (DCT) is applied to the image, and high-frequency components are removed to reduce the file size.

3. **Hadamard Compression**: Hadamard Transform is applied to the image, and the high-frequency components are set to zero to achieve compression.

## Prerequisites

To run the code in this repository, you will need the following prerequisites:

- Python 3.x
- OpenCV (cv2)
- Numpy
- Matplotlib
- Sympy

## Results
The code will display the original and compressed images, along with their respective sizes in kilobytes (KB).

## License
This code is licensed under the MIT License.
