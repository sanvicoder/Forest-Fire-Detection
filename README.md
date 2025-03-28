# AI-Driven Forest Fire Detection: Leveraging Machine Learning for Wildfire Prevention

## Overview
This project focuses on detecting and classifying forest fires using machine learning and deep learning models. The dataset contains images of fire and non-fire scenarios, and various models like SVM, AdaBoost, XGBoost, and CNN are trained to classify them effectively. The goal is to develop a reliable system for early fire detection to aid in wildfire prevention efforts.

## Dataset
The dataset used in this project is the **Forest Fire Images Dataset** from Kaggle, consisting of:
- **Train Data:** Fire and Non-Fire images
- **Test Data:** Fire and Non-Fire images

Dataset Path Structure:
```
/kaggle/input/forest-fire-images/Data/
  ├── Train_Data
  │   ├── Fire
  │   ├── Non_Fire
  ├── Test_Data
      ├── Fire
      ├── Non_Fire
```

## Methodology
1. **Data Preprocessing**
   - Image augmentation, resizing, and normalization
   - Splitting data into training and testing sets
2. **Feature Extraction & Model Training**
   - Traditional ML models: SVM, AdaBoost, XGBoost
   - Deep Learning: Convolutional Neural Network (CNN)
3. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score, MCC, and Confusion Matrix

## Experimental Results
The following models were tested and evaluated:

| Measure     | SVM  | AdaBoost | XGBoost | CNN  |
|-------------|------|---------|---------|------|
| Accuracy    | 0.86 | 0.82    | 0.872   | 0.94 |
| Precision   | 0.86 | 0.82    | 0.87    | 0.95 |
| F1-Score    | 0.87 | 0.82    | 0.87    | 0.94 |
| MCC         | 0.72 | 0.71    | 0.75    | 0.89 |

The CNN model performed the best, achieving the highest accuracy and F1-score.

## Key Features
-Image classification using ML & DL models  
-Model performance comparison & visualization  
-Data preprocessing & augmentation  
-Fire detection for wildfire prevention  
