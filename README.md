# 😊 Facial Emotion Recognition using Deep Learning

## 📌 Project Overview
This project was developed as part of my **AI/ML Internship**. The goal is to build a Deep Learning-based Facial Emotion Recognition system that can classify human facial expressions into different emotion categories.

The model uses **Computer Vision and Transfer Learning** techniques to recognize emotions from facial images.

---

## 🎯 Objective
- Detect facial emotions from input images.
- Train a Deep Learning model for multi-class emotion classification.
- Evaluate model performance using accuracy, confusion matrix, and classification metrics.
- Test the model on unseen facial images.

---

## 🗂️ Dataset
The project uses a facial emotion dataset containing 7 emotion classes:

- 😠 Angry
- 🤢 Disgust
- 😨 Fear
- 😊 Happy
- 😐 Neutral
- 😢 Sad
- 😲 Surprise

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔄 Project Workflow

Data Collection
↓
Data Loading & Exploration
↓
Image Preprocessing
↓
Data Augmentation
↓
Model Building (MobileNetV2)
↓
Model Training
↓
Model Evaluation
↓
Emotion Prediction on Unseen Images

---

## 🧠 Model Details

- **Base Model:** MobileNetV2
- **Learning Approach:** Transfer Learning
- **Input Image Size:** 224 × 224
- **Output Classes:** 7 Emotions
- **Evaluation Metrics:**
  - Accuracy
  - Loss
  - Confusion Matrix
  - Classification Report

---

## 📊 Results

The trained model was evaluated on the test dataset and performance was analyzed using:

- Training & Validation Accuracy Graphs
- Training & Validation Loss Graphs
- Confusion Matrix
- Classification Report

---

## 📁 Repository Structure

Facial-Emotion-Recognition/
│
├── notebooks/
│ ├── phase2_data_loading.ipynb
│ ├── phase3_preprocessing.ipynb
│ ├── phase4_model_training.ipynb
│ ├── phase5_evaluation.ipynb
│ └── phase6_prediction.ipynb
│
├── models/
│ └── best_model.keras
│
├── outputs/
│ ├── graphs/
│ ├── confusion_matrix.png
│ └── predictions/
│
├── README.md
└── requirements.txt

## 🚀 Future Improvements

- Improve accuracy with better fine-tuning.
- Add real-time emotion detection using webcam.
- Deploy the model using Flask/FastAPI.
- Optimize the model for mobile applications.
