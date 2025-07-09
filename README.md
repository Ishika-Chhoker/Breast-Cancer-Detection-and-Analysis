# Breast Cancer Detection and Analysis

## Description

**Breast Cancer Detection and Analysis** is a deep learning-based project focused on detecting and visualizing malignant regions in breast histopathology images using Convolutional Neural Networks (CNNs). The main objective is to assist in early diagnosis by automatically identifying patterns that indicate the presence of breast cancer, particularly **Invasive Ductal Carcinoma (IDC)**.

This project uses a dataset of over 90,000 labeled histopathology images and achieves an accuracy of **93.13%** in classifying cancerous vs. non-cancerous cells. It serves as a practical application of artificial intelligence in the medical field, aimed at improving both the speed and reliability of cancer diagnosis.

---

## Highlights

- Detects Invasive Ductal Carcinoma (IDC) using deep learning.
- Achieved an accuracy of 93.13% in classification.
- Dataset used includes 64,583 IDC-negative images and 25,417 IDC-positive images.
- Implements Convolutional Neural Networks for image-based feature extraction and classification.
- Encourages AI-driven advancements in medical imaging and diagnostics.

---

## Methodology

### 1. Deep Learning & CNNs

The project employs Convolutional Neural Networks (CNNs), which are particularly effective in analyzing image data. CNNs are composed of convolution layers, pooling layers, and fully connected layers. These layers work together to extract hierarchical features from input images and classify them based on the learned patterns.

Each layer of the CNN applies filters to extract important features from the input image, reducing its dimensions while preserving essential data. Brighter pixels are often emphasized to improve border detection, which is critical for isolating tumor regions. Pooling and activation functions are applied throughout the network to refine the learning process.

The model processes RGB images resized to 128x128 pixels. The size, number of filters, and stride are selected based on experimentation to achieve optimal performance without overfitting.

---

## Medical Relevance

Invasive Ductal Carcinoma (IDC) is the most common form of breast cancer, responsible for approximately 80% of cases. This condition originates in the milk ducts and spreads to nearby tissue. Early and accurate detection is crucial for effective treatment, as survival rates are significantly higher when the cancer is localized and identified early.

Traditional diagnostic methods, including mammography and MRI, are often limited in detecting small or residual tumors. The use of CNNs helps in identifying patterns that might be missed during manual analysis, enabling better support for radiologists and clinicians.

This system aligns with ongoing efforts in the medical research community to enhance diagnostic techniques through machine learning, making it a valuable step toward automation in cancer detection.
