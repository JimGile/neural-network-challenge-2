DU-VIRT-AI-PT-05-2024-U-LOLC-MWTH - Module 19 - Neural Network Challenge 2 (Sep 26, 2024)

# Module 19 Challenge - Neural Network Multiclass Classification with CNNs

[notebooks/attrition.ipynb](https://github.com/JimGile/neural-network-challenge-2/blob/main/notebooks/attrition.ipynb)

## Focus

Module 19 focuses on part 2 of neural networks and deep learning. It starts with image data preprocessing, moves on to image classification, and finishes with multiclass classification and branching.

## Day 1 - Preprocessing Image Data

* Stacked RGB channels
* Normalization
* Resizing
* Data augmentation
* Label image data for supervised learning

## Day 2 - Image Classification With Convolutional Neural Networks

* Convolution: A mathematical operation that blends or combines two sets of data to create a third set.
  * Filters and Kernels - Reduce the size of the image to a smaller grid of pixels.
    * Sobel edge detection
    * Gaussian blur
    * Emboss
    * Sharpen
* Convolutional Neural Network (CNN): a type of artificial neural network that is trained to recognize patterns in images.
  * Input Layer
  * Convolutional Layer
  * Pooling Layer
  * Flatten Layer
  * Output Layer
* Data Augmentation
  * Create new images from existing images: rotate, flip, blur, color, grayscale, noise, etc.
  * Add dimensions to input data shape: batch size, height, width, channels

## Day 3 - Multiclass Image Classification With CNNs

* Branching
  * Output from CNN layers can be fed into other CNN layers (branches) for multiclass classification.
* Output Activation Functions
  * Softmax: set of mutually exclusive outcome probabilities (each inputwill belong to only one of multiple output nodes)
  * Sigmoid: outcomes are independent of each other (each input could belong to multiple output nodes)

## Challenge

The challenge is to create a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

## Solution

The solution is in the Jupyter Notebook file [notebooks/attrition.ipynb](https://github.com/JimGile/neural-network-challenge-2/blob/main/notebooks/attrition.ipynb).
