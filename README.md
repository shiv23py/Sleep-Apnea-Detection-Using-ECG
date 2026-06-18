# Sleep Apnea Detection Using ECG Signals

## Project Overview

This project focuses on automatic detection of Sleep Apnea using ECG signals from the PhysioNet Apnea-ECG Database.

Sleep apnea is a common sleep disorder characterized by repeated pauses in breathing during sleep. Early detection can improve diagnosis and treatment outcomes.

---

## Dataset

Source: PhysioNet Apnea-ECG Database

- ECG Sampling Frequency: 100 Hz
- Records: 70
- Labels:
  - A : Apnea
  - N : Normal

---

## Methodology

### 1. ECG Signal Processing
- ECG loading using WFDB
- Signal segmentation into 60-second windows

### 2. Feature Extraction
HRV-based features extracted using NeuroKit2:

- Mean RR Interval
- SDNN
- RMSSD
- Heart Rate
- Statistical Features

### 3. Data Preprocessing
- Label Encoding
- Feature Scaling
- Train-Test Split

### 4. Machine Learning Models

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

### 5. Evaluation

Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Cross Validation

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- WFDB
- NeuroKit2

---

## Project Workflow

ECG Signal
↓
Segmentation
↓
HRV Feature Extraction
↓
Feature Scaling
↓
Machine Learning Models
↓
Sleep Apnea Classification

---

## Results

The models successfully classified apnea and normal ECG segments using HRV features.

Random Forest showed strong performance among the tested models.

---

## Future Improvements

- Deep Learning (CNN/LSTM)
- End-to-End ECG Classification
- Real-Time Monitoring System
- Wearable Device Integration

---

## Author

Shivam Pandey

M.Tech Biomedical Engineering
IIIT Allahabad
