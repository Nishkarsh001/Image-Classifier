Nishkarsh001.Image-Classifier
# Image-Classifier

# Humpback Whale Identification
## Problem Statement
The goal of this project is to identify and categorize the whales into different categories based on the images of its tail. It helps the scientists who are working in the whale conservation by using photo surveillance to monitor ocean activity.

## Data scource
Used data from Kaggle (https://www.kaggle.com/c/humpback-whale-identification)

## Approach:
Since the data is imbalanced I used Python and OpenCV to perform Image preprocessing and Data Augmentation by cropping, padding, horizontal flipping to generate 47k images. 

## Results
Built a convolutional neural network (CNN) model using keras to classify the whales with the cross-validation accuracy of 96%

