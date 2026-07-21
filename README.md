# Avocado-Condition-Classification-Computer-Vision-Pipeline
## 📌 Project Overview

This project focuses on automatically identifying diseases in oranges using image classification techniques. Two different approaches are implemented and compared:

- Classical Computer Vision (HSV + LBP + SVM)
- Deep Learning (MobileNetV2 Transfer Learning)

The objective is to evaluate the performance of traditional machine learning techniques against modern deep learning models for agricultural disease detection.

---

## 🎯 Objectives

- Detect diseases in oranges from images.
- Compare Classical Computer Vision with Deep Learning.
- Evaluate the strengths and limitations of each approach.
- Build an efficient image classification pipeline.

  
## 🦠 Disease Classes

The dataset contains four classes:

- 🍊 Fresh
- 🟢 Greening
- ⚫ Black Spot
- 🟠 Canker

---

## 📂 Dataset

The dataset consists of images categorized into four disease classes.

### Dataset Structure

```
dataset/
│
├── train/
│   ├── Fresh/
│   ├── Greening/
│   ├── Blackspot/
│   └── Canker/
│
└── test/
    ├── Fresh/
    ├── Greening/
    ├── Blackspot/
    └── Canker/
```

---

## 🔍 Data Preprocessing

The following preprocessing techniques were applied:

- Duplicate image removal
- Data cleaning
- Image resizing
- Image normalization
- Dataset splitting
- Data augmentation (for MobileNetV2)

---

## 🛠 Methodology

### 1️⃣ Classical Computer Vision Pipeline

- Image Loading
- HSV Color Feature Extraction
- Local Binary Pattern (LBP) Texture Features
- Feature Scaling
- Support Vector Machine (SVM) Classification

---

### 2️⃣ Deep Learning Pipeline

- MobileNetV2 (Transfer Learning)
- Image Augmentation
- Fine Tuning
- Softmax Classification Layer

---

## 💻 Technologies Used

- Python
- Google Colab
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- MobileNetV2

---

## 📊 Model Performance

| Model | Accuracy |
|--------|---------:|
| HSV + LBP + SVM | **95.5%** |
| MobileNetV2 | **94.4%** |

### Performance Comparison

- Classical Computer Vision achieved slightly higher accuracy.
- MobileNetV2 demonstrated strong generalization capabilities.
- Both approaches effectively classified orange diseases.

---

## 📈 Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

