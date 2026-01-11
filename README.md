# ♻️ Classification of Garbage using CNN

A deep learning project that classifies garbage images into different categories using a **Convolutional Neural Network (CNN)**.  
This project aims to support **automated waste segregation** and contribute to smarter and more efficient waste management systems.

---

## 📌 Project Overview

Waste segregation is a major challenge in modern waste management. Manual classification is inefficient and prone to errors.  
This project uses **Computer Vision and Deep Learning** techniques to automatically classify garbage images into predefined categories.

The CNN model learns visual features such as shape, texture, and color to accurately identify different types of waste.

---

## 🧠 Technologies & Tools Used

- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow / Keras  
- **Libraries:** NumPy, Matplotlib, OpenCV  
- **Model:** Convolutional Neural Network (CNN)  
- **Dataset:** Image-based garbage classification dataset  

---

## 🗂️ Garbage Categories

The model classifies waste into multiple categories, such as:

- Plastic  
- Paper  
- Metal  
- Glass  
- Organic / Biodegradable Waste  

*(Exact categories depend on the dataset used.)*

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Image resizing and normalization
   - Dataset splitting (training and testing)
   - Data augmentation for better generalization

2. **CNN Architecture**
   - Convolutional layers for feature extraction
   - MaxPooling layers to reduce spatial dimensions
   - Fully Connected (Dense) layers for classification
   - Softmax activation for multi-class prediction

3. **Model Training**
   - Optimizer: Adam
   - Loss Function: Categorical Cross-Entropy
   - Evaluation using accuracy and loss metrics

4. **Evaluation**
   - Tested on unseen images
   - Visualized predictions and performance curves

---

## 📊 Results

- Achieved satisfactory accuracy on validation data
- Successfully distinguishes between different garbage categories
- Demonstrates the effectiveness of CNNs for real-world environmental applications

---

## 🌱 Future Enhancements

-Apply transfer learning (VGG, ResNet, MobileNet)
-Deploy the model as a web or mobile application
-Enable real-time garbage classification using a camera
-Expand dataset for improved accuracy and robustness

---

## 👨‍💻 Author

Jivesh Gupta
BCA – Artificial Intelligence & Machine Learning
Python | Machine Learning | Data Analysis

---

## ⭐ Acknowledgements

This project was developed as part of academic learning and hands-on practice in deep learning and computer vision.


