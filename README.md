# Image Processing with Sobel Operator and K-Means Clustering
## Overview
This project implements image processing techniques using the Sobel operator for edge detection and K-means clustering for image segmentation. The code utilizes libraries such as NumPy, OpenCV, and Matplotlib to perform operations on images and visualize the results.

## Requirements
Python 3.x
NumPy
OpenCV
Matplotlib
Pillow
Rasterio (optional for additional functionalities)

## Usage
- Sobel Operator: The Sobel operator is applied to detect edges in an image.
- The input image should be in JPEG format and named imsat TP3.jpg.
- The output will be three images corresponding to the edges detected in the red, green, and blue channels.
- K-means Clustering: The K-means algorithm is used to segment the image into K clusters based on color.
- The image is read, and the colors are clustered into the specified number of groups.


# Functions and Classes
def euclidean_distance(x1, x2):
    ...

class KMeans():
    ...
Sobel Operator
The Sobel operator detects edges by calculating the gradient of image intensity. It uses two kernels, one for horizontal and one for vertical gradients.

K-means Clustering
The K-means class implements the K-means clustering algorithm, which clusters the image pixels into K groups based on their RGB values.
