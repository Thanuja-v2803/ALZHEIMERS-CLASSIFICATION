# 🧠 AlzPredict: Alzheimer’s Disease Classification using Deep Learning

## 📌 Abstract
AlzPredict is a deep learning-based system designed to classify stages of Alzheimer’s disease from brain MRI images. The model leverages a ResNet-18 architecture to extract high-level features and provide accurate stage-wise predictions, supporting early diagnosis.

---

## 🎯 Objectives
- Develop an automated system for Alzheimer’s stage classification  
- Improve early detection using deep learning techniques  
- Analyze MRI images efficiently with high accuracy  

---

## 🧠 Methodology
1. **Data Preprocessing**
   - Image resizing and normalization  
   - Train-test split  

2. **Model Architecture**
   - ResNet-18 (pretrained CNN)  
   - Fine-tuned for medical image classification  

3. **Training**
   - Loss Function: Cross-Entropy Loss  
   - Optimizer: Adam  
   - Evaluation Metric: Accuracy  

4. **Prediction**
   - Classifies MRI images into Alzheimer’s stages  

---

## 📊 Dataset
The dataset consists of brain MRI images categorized into:
- Non-Demented  
- Very Mild Demented  
- Mild Demented  
- Moderate Demented  

⚠️ Due to GitHub size limitations, the dataset is hosted externally.  
👉 **Dataset Link:** (https://drive.google.com/drive/folders/1oyFvyMgUoX4y7EgeZIbnnd2IxUofgfIL?usp=drive_link)

---

## ⚙️ Tech Stack
- Python  
- PyTorch  
- NumPy, Matplotlib  
- Google Colab  

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
