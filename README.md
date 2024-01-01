# Image Classification using Convolution and Filter Banks | Computer Vision

This project is a comprehensive exploration of image processing and computer vision techniques using Python. The project is divided into several sections, each focusing on a different aspect of image processing. The main libraries used in this project are NumPy, OpenCV, and Matplotlib.

## Overview

The project covers the following topics:

1. Understanding Image Matrix
2. Zero-Padding
3. 2D Convolution
4. Edge Detection
5. Combining Filters
6. Image Classification

## Understanding Image Matrix

In this section, an image is loaded using OpenCV's `imread` function. The image is then converted to grayscale using the `cvtColor` function. The dimensions of the original and grayscale images are printed to understand the structure of the image matrix.

## Zero-Padding

Zero-padding is a process that adds zeros around the border of an image. This is useful in convolution operations where the filter might go beyond the image boundaries. A function `zero_pad` is defined to add padding to an image.

## 2D Convolution

Convolution is a mathematical operation that is fundamental to many common image processing filters. Convolution provides a way of 'multiplying together' two arrays of numbers, generally of different sizes, but of the same dimensionality, to produce a third array of numbers of the same dimensionality. A function `conv2D` is defined to perform 2D convolution on an image.

## Edge Detection

Edge detection is an image processing technique for finding the boundaries of objects within images. It works by detecting discontinuities in brightness. Different types of filters are applied to the images to detect horizontal, vertical, and diagonal edges.

## Combining Filters

In this section, multiple filters are combined to detect different features in an image. The filters are applied to the image and the results are displayed.

## Image Classification

In the final section, a simple image classification task is performed. The images are preprocessed and feature vectors are extracted using the filters. The feature vectors are then used to classify the images.

Here is a step-by-step breakdown of the code:

1. Import the necessary libraries (NumPy, OpenCV, and Matplotlib).
2. Load an image and convert it to grayscale.
3. Implement zero-padding.
4. Implement 2D convolution.
5. Apply different filters to the image to detect edges.
6. Combine multiple filters and apply them to the image.
7. Preprocess the images for classification.
8. Extract feature vectors from the images using the filters.
9. Classify the images based on the feature vectors.

This project provides a good understanding of image processing techniques and their implementation in Python. It can be further extended by implementing more advanced techniques and using larger and more complex datasets.