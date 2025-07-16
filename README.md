# A Comparative Study on Facial Emotion Recognition

This project presents a comparative study of various traditional and deep learning methods for Facial Emotion Recognition (FER). It includes implementations of LBP, HOG, SIFT, ORB, and a real-time FER system using a pre-trained VGG16 model. The goal is to evaluate and compare their effectiveness in classifying human emotions from facial images.

## 📌 Features

- Traditional Feature Descriptors:  
  - Local Binary Patterns (LBP)  
  - Histogram of Oriented Gradients (HOG)  
  - Scale-Invariant Feature Transform (SIFT)  
  - Oriented FAST and Rotated BRIEF (ORB)

- Deep Learning Approach:  
  - Pre-trained VGG16 model fine-tuned for emotion classification  
  - Real-time emotion prediction from webcam feed  
  - Trained on the FER2013 dataset

- Comparative Analysis:
  - Accuracy, precision, recall, and confusion matrices for each method
  - Performance visualization through graphs and charts


## 🧠 Datasets Used

- [FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013):  
  Contains grayscale facial images labeled with 7 emotion categories:  
  `Angry`, `Disgust`, `Fear`, `Happy`, `Sad`, `Surprise`, `Neutral`

## 🧪 Evaluation Metrics

- Accuracy
- Precision & Recall
- Confusion Matrix
- Real-time Inference Speed

## 📊 Results Summary

| Method | Accuracy | Pros | Cons |
|--------|----------|------|------|
| LBP    | ~62%     | Fast & Lightweight | Sensitive to noise |
| HOG    | ~63%     | Good edge detection | High dimensionality |
| SIFT   | ~72%     | Scale & rotation invariant | Computationally expensive |
| ORB    | ~73%     | Faster than SIFT | Less accurate |
| VGG16  | ~81%     | High accuracy | Requires GPU & training time |

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy, Matplotlib
- TensorFlow / Keras
- Scikit-learn

## ✍️ Author

**Mahesh Nayak**  
[GitHub](https://github.com/mahesh-nayak53) | [LinkedIn](https://www.linkedin.com/in/mahesh-nayak-008159281/)


