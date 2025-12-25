# ATCM: A Method for Land-Water Classification from Satellite Images using MobileNetV2 
-----------------------------------------------------------------------------------------------------------------------------
A comprehensive deep learning project comparing the performance of multiple state-of-the-art convolutional neural network architectures for binary classification of satellite images into "Water" and "Land" categories.

## Problem Statement
-----------------------------------------------------------------------------------------------------------------------------
Automated classification of water bodies from satellite imagery is crucial for environmental monitoring, urban planning, and disaster management. This project implements and compares various deep learning models to accurately distinguish between water and land regions in images.

## Preprocessing Steps
-----------------------------------------------------------------------------------------------------------------------------
* Image Resizing: 128×128 pixels
* Denoising: Gaussian blur
* Sharpening: Custom sharpening filter
* Normalization: Pixel values scaled to [0, 1]
