# 🏏 Mobile Hawkeye — LBW Prediction System

A machine learning-based cricket LBW prediction system that combines
computer vision, trajectory analysis, and ensemble classification
to make LBW predictions using smartphone-recorded videos.

## 📌 Project Overview

The system analyzes cricket deliveries recorded from two camera angles:
- Front View (FV)
- Side View (SV)

It uses OpenCV for ball tracking, physics-inspired feature extraction,
and machine learning classifiers to predict LBW decisions.

## ⚙️ System Architecture

1. Video Input — Front-view and side-view cricket videos.
2. Ball Tracking — OpenCV, HSV color segmentation, and contour detection.
3. Feature Extraction — Trajectory, speed, impact point, and pitch location.
4. ML Classification — Random Forest, Gradient Boosting, and SVM.
5. Final Prediction — Soft-voting ensemble produces an LBW prediction.

## 🧠 Machine Learning Models

- Random Forest
- Gradient Boosting Classifier
- Support Vector Machine (RBF kernel)
- Voting Classifier with soft voting

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- SciPy
- Matplotlib

## 📊 Results

The project presentation reports the following held-out test results:

- Test Accuracy: 76.5%
- Correct Predictions: 13 out of 17 test samples

The small test set means these results should be interpreted cautiously.
Improving dataset size and LBW-class recall are important future goals.

## 🚀 Future Scope

- Expand and balance the dataset.
- Improve ball tracking using deep learning-based object detection.
- Explore 3D trajectory reconstruction.
- Develop a mobile application for field use.

## 📂 Repository Contents

- `LBW_Final (1).ipynb` — Python notebook containing the project implementation.
- `LBW_Hawkeye_Results_Updated (1).pptx.pdf` — Project presentation.

## 👥 Team

Developed as a Machine Learning project at VNIT Nagpur.
