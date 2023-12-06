# Image-Classification-of-Celebrities-using-CNN

### Introduction
This demonstrates celebrity image classification using a Convolutional Neural Network (CNN). The aim is to correctly identify five different celebrities: Lionel Messi, Maria Sharapova, Roger Federer, Serena Williams, and Virat Kohli.

### Dataset
The dataset comprises images of the five celebrities. Images were loaded, resized, and split into training and testing sets.

### Model Architecture
The CNN model consists of Conv2D layers with ReLU activation, MaxPooling2D layers, Flattening layer, Dense layers with ReLU activation, a Dropout layer, and a final Dense layer with Softmax activation for classification.

### Training
The model was compiled using the Adam optimizer and trained on the training set for 50 epochs.

### Evaluation
The model achieved an accuracy of approximately 73.53% on the test set. A classification report was generated, detailing precision, recall, and F1-score for each class.

### Prediction
Functions to preprocess single images and predict their classes using the trained model were defined. Predictions for a set of test images were made and matched the expected classes accurately.
