# 😷 Face Mask Detection using Deep Learning

This project builds a **deep learning model** to automatically detect whether a person is wearing a **face mask** or **not**.  
It can be used in real-time applications such as monitoring systems in public places, offices, or healthcare facilities.  

---

## 📌 Overview

The COVID-19 pandemic highlighted the importance of face masks in reducing transmission.  
This project leverages **Convolutional Neural Networks (CNNs)** to classify images into two categories:  

- ✅ With Mask  
- ❌ Without Mask  

---

## 📊 Dataset

- Dataset used: [Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)  
- Classes: `with_mask` and `without_mask`  
- Size: ~7,000 images  
- Images are preprocessed and resized before training  

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Resized all images to `224x224`
   - Normalized pixel values  
   - Train/Test split

2. **Model**
   - Implemented a **CNN** (Convolutional Neural Network)  
   - Optionally, used **Transfer Learning** with MobileNetV2 for higher accuracy  
   - Output layer with **softmax activation** for binary classification  

3. **Training**
   - Loss: Categorical Crossentropy  
   - Optimizer: Adam  
   - Metrics: Accuracy  

4. **Evaluation**
   - Confusion Matrix  
   - Precision, Recall, F1-score  

---

## 🚀 Results

- **Accuracy:** ~95% on test dataset  
- Model works in **real-time webcam detection** with OpenCV integration  

---

👤 Author

Hadis Zare
📧 Profi.hadiszare@gmail.com

