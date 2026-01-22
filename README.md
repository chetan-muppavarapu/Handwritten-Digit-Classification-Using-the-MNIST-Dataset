# Handwritten-Digit-Classification-Using-the-MNIST-Dataset
Built a CNN-based handwritten digit classifier using the MNIST dataset. Achieved high accuracy and confidence through effective preprocessing and model design. Used visual diagnostics such as mean digit images, confidence distributions, and PCA projections to interpret model behavior, strengths, and limitations.

## Project Overview
The objective of this project is to design, train, and analyze a deep learning model capable of recognizing handwritten digits. Beyond achieving high classification accuracy, the project emphasizes model interpretability through visual diagnostics that explain how the network learns and separates digit patterns.

The workflow includes data preprocessing, CNN model training, evaluation on test data, and detailed visualization-based analysis.

## Dataset

**MNIST Handwritten Digits Dataset**

Source: Yann LeCun, NYU  
The dataset contains 70,000 grayscale images of handwritten digits (0–9), each sized 28×28 pixels. MNIST is widely used as a benchmark for evaluating image classification models.

## Methodology

### Data Preprocessing

Images were normalized and reshaped to meet CNN input requirements. Basic augmentation techniques were applied to improve generalization and reduce overfitting.

### Convolutional Neural Network (CNN)

A lightweight CNN architecture was implemented to extract spatial features from digit images. The model was trained using backpropagation and evaluated on a held-out test set.

### Model Interpretation and Visualization

Mean digit images were generated to visualize average handwriting patterns. Prediction confidence distributions were analyzed to assess model certainty. Principal Component Analysis (PCA) was applied to high-dimensional image data to visualize learned feature separability.

## Key Findings

The model achieved high accuracy with strong confidence on correct predictions.  
Clear digit clusters were observed in PCA projections, confirming effective feature extraction.  
Misclassifications occurred mainly between visually similar digits such as 3 and 5 or 8 and 9.  

## Tools & Technologies

Python  
TensorFlow / Keras  
NumPy  
Matplotlib  
Scikit-learn  

## Conclusion

This project demonstrates that a well-designed lightweight CNN can achieve excellent performance on handwritten digit recognition tasks. Visualization techniques such as PCA and confidence analysis provided valuable insight into model behavior, forming a strong foundation for extending the approach to deeper architectures and more complex datasets.

## Course Information

Course Name: AIT 736 – Applied Machine Learning  
Instructor: Professor Yang Lei
