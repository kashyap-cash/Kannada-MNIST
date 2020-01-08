# Kannada-MNIST

## 1. Problem Statement

The goal of this competition is to classify hand written image of kannada language digit recognition. The goal also includes to joining the kaggle competition and submitting the code.

## 2. Dataset

Input Features: 
  - Image with pixel dimensions: 28 x 28 pixels
  - Training Data: 60000
  - Test Data: 5000

Labels:
  - 0 to 9 digit recognition in kannada language
  
## 3. Data Pre-processing

- Standardized Scaling
- Split the dataset

## 4. Install keras & tensorflow

Install the tensorflow by following steps:

  - pip install --upgrade pip
  - pip install tensorflow
  - pip install tf-nightly

Install keras by following steps:

  - sudo pip install keras
  - pip install keras

## 5. Building the model

Complexity:
- First Convolution Layer with 64 3x3 kernels
- Fist Max pooling layer with pool size 2x2
- Second Convolution Layer with 128 3x3 kernels
- Second Max pooling layer with pool size 2x2
- Flatten Layer
- First Hidden Layer with 256 neurons 
- Second Hidden Layer with 128 neurons
- Output Layer with 10 neurons

Compiler:
  - Adam Optimizer
  - Sparse Cross Entropy
  - Accuracy metrics

## 6. Conclusion

The Kannada data MNIST image classification project consist of hand written image classification of kannada language, using convolution neural network algorithms. Using two convolution layers the model is trained and the training accuracy is achieved to 98.12% while the test accuracy reached to 98.5% and public score of 0.9626 in kaggle.

In future, the model could be trained using random forest algorithm to reduce the complexity and time to train the model as the random forest is used for multi-class feature detection.





