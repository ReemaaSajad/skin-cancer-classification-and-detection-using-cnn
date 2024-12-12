# Skin Cancer Detection and Classification using Convolutional Neural Networks

## Overview

This research project explores the application of deep learning techniques for automated skin cancer detection and classification. By leveraging Convolutional Neural Networks (CNNs) and additional metadata, the project aims to assist healthcare professionals in early and accurate skin cancer diagnosis.

## Key Features

- Automated detection of multiple skin cancer types
- Uses EfficientNet-B7 as the base model for image feature extraction
- Incorporates metadata (age, anatomical site, gender) to improve classification
- Handles 9 different skin lesion categories

## Dataset

- Source: Kaggle ISIC 2019 Dataset
- Total Images: Approximately 25,000
- Categories:
  - Basal Cell Carcinoma
  - Squamous Cell Carcinoma
  - Melanoma
  - Melanocytic Nevus
  - Actinic Keratosis
  - Benign Keratosis
  - Dermatofibroma
  - Vascular Lesion
  - Normal Skin

## Methodology

### Preprocessing
- Image Resizing: 380x380 pixels
- Data Augmentation: 
  - Horizontal and vertical flipping
  - Random rotation
- Normalization using ImageNet mean and standard values
- Metadata preprocessing with label encoding and standardization

### Model Architecture
- Base Model: EfficientNet-B7
- Custom Architecture:
  - CNN for image feature extraction
  - Sequential network for metadata processing
  - Concatenated features for final classification

## Performance

- Validation Accuracy: 84.29%
- Low overfitting
- Effective multi-label classification

## Key Contributions

- Demonstrated the potential of combining deep learning with metadata
- Improved skin cancer detection accuracy
- Showcased AI's potential in medical imaging diagnostics

## Limitations and Future Work

- Address class imbalances
- Improve model interpretability
- Expand dataset diversity
- Clinical setting validation

## References

1. World Health Organization
2. ISIC 2019 Dataset (Kaggle)
