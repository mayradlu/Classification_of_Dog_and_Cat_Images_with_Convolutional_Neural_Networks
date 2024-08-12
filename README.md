# Classification of Dog and Cat Images with Convolutional Neural Networks

## General Information
This project addresses binary classification of images of dogs and cats using convolutional neural networks (CNNs). Throughout the project, various CNN architectures, preprocessing techniques, and training strategies are explored to achieve the best possible performance.

## Theoretical Framework
Deep learning, a branch of machine learning, uses neural networks inspired by the human brain to learn from large amounts of data. CNNs are specifically designed for structured data in the form of images. They consist of three main types of layers:

**Convolutional Layer**: Applies filters to the image to extract features.

**Pooling Layer**: Reduces the dimensionality of the images, highlighting important features.

**Fully Connected Layer**: Produces the final output of the model.

## Project Data
Initially, 6,000 images of dogs and 6,000 images of cats were considered. However, an imbalance was observed when separating the training and test sets, resulting in poor performance for the classification of cats. To solve this, a subsampling was performed that balanced the images of both classes, resulting in a total of 11,685 images (5,842 dogs and 5,843 cats).

## Results
Accuracy for Cats (0): 87%
Recall: 0.65
F1-score: 0.75

Accuracy for Dogs (1): 71%
Recall: 0.90
F1-score: 0.80

Overall Accuracy: 0.77

## Python
Instructions for downloading libraries are already in the Python notebook
