# 🐟 Multiclass Fish Species Classification using Deep Learning  

This project focuses on building a **Deep Learning-based image classification system** that identifies different **fish species** from images. The classification is performed using both a **Custom CNN model** and a **Transfer Learning InceptionV3 model**. The final model is deployed using a **Streamlit web application**.

---

## 📌 Project Overview

The primary goal of this Capstone Project is to:
- Preprocess and analyze a custom fish dataset
- Apply data augmentation techniques  
- Train a **CNN model from scratch**  
- Train a **Transfer Learning model (InceptionV3)**
- Evaluate model performance using classification metrics  
- Save the best model for deployment  
- Build and deploy a **Streamlit-based prediction app**

This project demonstrates practical experience in:
✔ Deep Learning  
✔ Image Classification  
✔ Transfer Learning  
✔ Model Evaluation  
✔ Deployment with Streamlit  

---

## 🧠 Models Used

### 1️⃣ Custom CNN Model
- 3 Convolution Blocks (32 → 64 → 128 filters)
- Batch Normalization & MaxPooling
- Flatten + Dense Layers
- Dropout (0.5)
- Softmax Output Layer  
Used as baseline for comparison.

### 2️⃣ Transfer Learning — **InceptionV3**
- Pretrained on ImageNet  
- Top layers removed  
- Custom Dense layers added  
- Fine-tuned for fish species dataset  
- Best-performing model, deployed in Streamlit  

---

## 📊 Model Evaluation

Metrics computed:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Class-wise performance

These metrics help understand how well the model distinguishes between fish species.

---

## 🖼️ Streamlit App Features

- Upload an image (.jpg / .jpeg / .png)  
- Model predicts the **fish species**  
- Shows **confidence score**  
- Displays **Top-3 predictions**  
- Custom ocean-themed UI  
- Deployed locally or on cloud platforms

---

### **3. Upload an image**
The app will:
- Preprocess the image  
- Pass it through the InceptionV3 model  
- Display predicted species  

---

## 📦 Dataset Information

- Dataset contains folders of multiple fish species.  
- Images split into:
  - `train/`
  - `validation/`
  - `test/`
- Augmentation applied to training images:
  - Rotation  
  - Zoom  
  - Width/Height Shift  
  - Horizontal Flip  

---

## 🧪 Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- scikit-learn  
- PIL  
- Streamlit  

---

## 🌟 Results Summary

The **InceptionV3 Transfer Learning model** achieved the best accuracy and class-wise performance.  
This model was selected for deployment in the Streamlit application.

---

## ✨ Author

**Sai Vennela Yadavalli**  
---

## ✨ Quote
“Deep Learning is not about making computers think — it’s about teaching them to see.”
