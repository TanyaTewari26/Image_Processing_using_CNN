## Image Processing of CIFAR dataset using Convolutional Neural Network

This repository contains code and resources for performing image classification on the CIFAR-10 dataset using Convolutional Neural Networks (CNNs). 
CIFAR-10 is a well-known dataset consisting of 60,000 32x32 color images in 10 different classes, with 6,000 images per class.

## Convolutional Neural Network (CNNs)
A convolutional NN is a network that contains one or more convolutional layers. A convolutional layer allows the network to process spatial patterns (e.g., identify items within an image). 
For this reason, CNNs are commonly used for image identification and computer vision.

CNNs simplify images, converting them into the main lines or features. That simplified pattern is then fed into a more traditional neural network, which identifies the pattern.

The following is a typical architecture for CNNs:

Conv2D

MaxPooling2D

Dropout

Flatten

Dense

Dropout

Dense NN that uses Softmax (for >2 categories)

The convolutional layer applies a filter to a 3x3 collection of pixels. This process convolutes or reshapes the image into something simpler. 
For a 3 channel image, the convolution process converts the image into a black and white image.

Max pooling simplifies the image even further by using only the maximum value within a 2x2 window. 
This step further reduces image complexity by reducing its size, which speeds computation.

Flatten converts the 2D image data into 1D. This step prepares the data for the NN.

After Flatten is our traditional NN, which will identify the patterns, apply softmax, and make the final prediction.
