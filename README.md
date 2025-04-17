# Real-Time Face Recognition System using CNN and TensorFlow

## 📌 Overview
This project implements a real-time face recognition system using Convolutional Neural Networks (CNNs) in TensorFlow. It accurately identifies individuals using webcam input or images, making it ideal for security and user verification.

## 🚀 Features
- Real-time face detection and recognition
- CNN-based feature extraction and classification
- Trained on the Labeled Faces in the Wild (LFW) dataset
- Built using TensorFlow, Keras, OpenCV

## 🧠 Model Architecture
- Input: (224, 224, 3)
- Conv2D → MaxPooling2D × 3
- Flatten → Dense(512) → Dropout(0.5) → Dense(Softmax)

## 📁 Project Files
- `src/`: Source code
- `FinalProject.html`: Code walkthrough
- `Project_Report_Shivesh_Raj_Sahu.docx`: Detailed report
- `FinalProject_Presentation.pptx`: Summary presentation

## 🛠 Installation
```bash
pip install -r requirements.txt
