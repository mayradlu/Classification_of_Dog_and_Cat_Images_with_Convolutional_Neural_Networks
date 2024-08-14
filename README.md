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
* Cats: 0
* Dogs: 1
<p align="center">
  <img src="https://github.com/user-attachments/assets/cff03a37-787a-4664-bbd5-5ab0819b407f" alt="imagen" width="600">
</p>

Overall Accuracy: 0.77

## Example of Classification
<p align="center">
  <img src="https://github.com/user-attachments/assets/92b6f0af-b534-4c2c-b233-a2ea49318269" alt="imagen" width="600">
</p>

## Python
Instructions for downloading libraries are already in the Python notebook
