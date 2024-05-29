# Fruit Maturity Level Classification

## Project Overview
This project focuses on classifying the maturity levels of fruits, specifically rambutan, using machine learning techniques. The dataset for this project was self-collected, consisting of high-resolution images with a size of 3456 × 4608 pixels.

## Preprocessing Steps
To prepare the images for classification, the following preprocessing steps were applied:

1. **Remove Image Background**: The background of the images was removed to focus solely on the fruit.
2. **Convert to HSV**: The images were converted from RGB to HSV color space to better capture the color features.
3. **Resize Image to 256x256**: The images were resized to a standard size of 256x256 pixels.
4. **Extract HSV Feature**: Features were extracted from the HSV color space to be used in the model.

## Model Development
Two machine learning models were developed and evaluated for this classification task:

- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**

## Results
The best model accuracy was achieved by the K-Nearest Neighbors (KNN) model, reaching an accuracy of 100% on training set and 97.38% on the test set data.

## Conclusion
This project successfully demonstrates the application of machine learning techniques for fruit maturity classification, with KNN proving to be the most effective model for this dataset.