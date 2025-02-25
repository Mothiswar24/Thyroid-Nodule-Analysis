# Thyroid-Nodule-Analysis

**Overview:** <br>
This project focuses on developing an automated diagnostic tool to classify thyroid nodules as benign or malignant using deep learning techniques. By leveraging ultrasound imaging and advanced machine learning models, the system aims to enhance diagnostic accuracy, minimize human error, and reduce the need for invasive procedures.

**Approach & Technologies Used**<br>
  **Deep Learning Models Implemented:**<br>
    🔹CNN (Convolutional Neural Networks): Extracts spatial features from ultrasound images.<br>
    🔹LSTM (Long Short-Term Memory): Handles sequential data and enhances contextual learning.<br>
    🔹Ensemble Model (CNN + LSTM): Combines spatial and temporal features for improved classification.<br>
    🔹CBAM (Convolutional Block Attention Module): Enhances feature extraction by focusing on relevant image regions.<br>
    🔹Transfer Learning (VGG, ResNet): Uses pre-trained models to extract high-level features.<br>
    🔹Machine Learning Classifiers (KNN, SVM, Random Forest): Utilized for feature-based classification.
    
**Dataset:**<br>
🔹Algerian Ultrasound Images Thyroid Dataset (AUITD) with 1,937 labeled images (benign, malignant, normal).

**Data Processing Techniques:**<br>
🔹Image Preprocessing: Normalization, resizing, noise removal.<br>
🔹Data Augmentation: Rotation, flipping, zooming to increase dataset variability.
      
**Evaluation Metrics:**<br>
🔹Accuracy, Precision, Recall, F1-score to measure classification performance.
      
**Key Findings:**<br>
🔹LSTM model achieved the highest test accuracy of 73.13%.
      <br>🔹Overfitting observed due to class imbalance; <br>🔹Future improvements include GANs & SMOTE for synthetic data generation.
