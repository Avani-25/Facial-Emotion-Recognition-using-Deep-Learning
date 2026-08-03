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
- VScode

---

## 🔄 Project Workflow

| Phase       | Work Done                             | Libraries Used                                                                |
| ----------- | ------------------------------------- | ----------------------------------------------------------------------------- |
| **Phase 1** | Project setup & dataset understanding | Python, OS, TensorFlow basics                                                 |
| **Phase 2** | Data Loading                          | TensorFlow `image_dataset_from_directory`, NumPy                              |
| **Phase 3** | Image Preprocessing & Augmentation    | TensorFlow/Keras preprocessing layers (`Resizing`, `Rescaling`, augmentation) |
| **Phase 4** | Model Building & Training             | TensorFlow/Keras, MobileNetV2                                                 |
| **Phase 5** | Model Evaluation                      | Matplotlib, Seaborn, Scikit-learn (confusion matrix, classification report)   |
| **Phase 6** | Prediction on unseen images           | TensorFlow/Keras image loading & preprocessing                                |


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

## Project Report


## 🚀 Future Improvements

- Improve accuracy with better fine-tuning.
- Add real-time emotion detection using webcam.
- Deploy the model using Flask/FastAPI.
- Optimize the model for mobile applications.
