# Facial-Recognition-with-Supervised-Learning

This project builds a machine learning model capable of distinguishing images of Arnold Schwarzenegger from images of other individuals.

## Objective

Develop a facial recognition classifier capable of identifying whether a given image belongs to Arnold Schwarzenegger or not.

## Dataset

The dataset is derived from the Labeled Faces in the Wild (LFW) dataset.

It contains:

40 images of Arnold Schwarzenegger  
150 images of other individuals  

The dataset was preprocessed using PCA to reduce dimensionality and extract the most relevant facial features.

### Columns

PC1, PC2, ... PCN  
Principal Components representing image features

Label  
1 → Arnold Schwarzenegger  
0 → Other individuals

## Method

The project applies a supervised classification approach.

Steps:

1. Load PCA-based facial feature dataset
2. Split dataset into training and testing sets
3. Train Logistic Regression classifier
4. Predict class labels
5. Evaluate performance using accuracy and classification metrics

## Libraries

pandas  
numpy  
scikit-learn
