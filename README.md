# Thyroid-Nodule-Analysis

**Overview:**
This project focuses on developing an automated diagnostic tool to classify thyroid nodules as benign or malignant using deep learning techniques. By leveraging ultrasound imaging and advanced machine learning models, the system aims to enhance diagnostic accuracy, minimize human error, and reduce the need for invasive procedures.

**Approach & Technologies Used**
  **Deep Learning Models Implemented:**
    🔹CNN (Convolutional Neural Networks): Extracts spatial features from ultrasound images.
    🔹LSTM (Long Short-Term Memory): Handles sequential data and enhances contextual learning.
    🔹Ensemble Model (CNN + LSTM): Combines spatial and temporal features for improved classification.
    🔹CBAM (Convolutional Block Attention Module): Enhances feature extraction by focusing on relevant image regions.
    🔹Transfer Learning (VGG, ResNet): Uses pre-trained models to extract high-level features.
    🔹Machine Learning Classifiers (KNN, SVM, Random Forest): Utilized for feature-based classification.
    
  🔹**Dataset:**
       Algerian Ultrasound Images Thyroid Dataset (AUITD) with 1,937 labeled images (benign, malignant, normal).

  🔹**Data Processing Techniques:**
      Image Preprocessing: Normalization, resizing, noise removal.
      Data Augmentation: Rotation, flipping, zooming to increase dataset variability.
      
  🔹**Evaluation Metrics:**
      Accuracy, Precision, Recall, F1-score to measure classification performance.
      
  🔹**Key Findings:**
      LSTM model achieved the highest test accuracy of 73.13%.
      Overfitting observed due to class imbalance; future improvements include GANs & SMOTE for synthetic data generation.
