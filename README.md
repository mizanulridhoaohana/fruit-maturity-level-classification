# Fruit Maturity Level Classification

## Tech Stack
<p>
  <img src="https://www.python.org/static/community_logos/python-logo.png" alt="Python" width="100" tyle="margin-right: 10px;">
  <img src="https://jupyter.org/assets/homepage/main-logo.svg" alt="Jupyter Notebook" width="40" tyle="margin-right: 100px;">
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="scikit-learn" width="100" tyle="margin-right: 100px;">
  <img src="https://numpy.org/images/logo.svg" alt="NumPy" width="50" tyle="margin-right: 100px;">
  <img src="https://opencv.org/wp-content/uploads/2020/07/OpenCV_logo_no_text.png" alt="OpenCV" width="50" tyle="margin-right: 100px;">
  <img src="https://matplotlib.org/_static/images/logo2.svg" alt="Matplotlib" width="100" tyle="margin-right: 100px;">
  <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn" width="100" tyle="margin-right: 100px;">
  <img src="https://pandas.pydata.org/static/img/pandas_white.svg" alt="Pandas" width="100" tyle="margin-right: 100px;">
</p>


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