##Plant Disease Detection Model

**Overview**
This project involves building a robust plant disease detection model using a dataset of 50,000 images across 38 distinct disease classes. The goal is to accurately identify diseases in plants through image classification.

**Dataset**
Images: 50,000 plant images
Classes: 38 distinct disease types
Source: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset
**Model Development**
1. *Custom CNN Model*
Architecture: A Convolutional Neural Network (CNN) was designed from scratch to classify plant diseases.
Accuracy: Achieved an accuracy of 88.2% on the test dataset.
2. *Pretrained Models*
Models Used: VGG16, ResNET50, DenseNET201, and InceptionV3 were employed to leverage transfer learning.
Best Model: InceptionV3 outperformed other models, achieving an accuracy of 92.8%.
**Requirements**
Python 3.x
Libraries:
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Seaborn
scikit-learn
Git LFS (for managing large files)
