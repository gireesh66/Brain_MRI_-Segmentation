# Brain_MRI_Segmentation
# 🧠 Brain Tumor Segmentation using U-Net

## 📌 Overview
This project focuses on **automatic brain tumor segmentation** from MRI images using a deep learning model based on the **U-Net architecture**.

The model takes MRI scans as input and predicts the tumor region as a segmentation mask, helping in faster and more accurate medical analysis.

---

## 🎯 Objectives
- Perform pixel-wise segmentation of brain tumors
- Handle medical image data (.tif format)
- Build an end-to-end deep learning pipeline
- Evaluate performance using segmentation metrics

---

## 🗂️ Dataset
- Brain MRI Segmentation Dataset (Kaggle)
- Contains MRI images and corresponding tumor masks
- Image format: `.tif`

---

## ⚙️ Tech Stack
- **Programming:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, OpenCV, Matplotlib  
- **Model:** U-Net Architecture  

---

## 🏗️ Project Pipeline

1. Data Loading & Preprocessing  
2. Image-Mask Pairing  
3. Normalization  
4. Train-Validation-Test Split  
5. Model Building (U-Net)  
6. Training with BCE + Dice Loss  
7. Prediction & Visualization  
8. Evaluation using Dice & IoU  

---

## 🧠 Model Architecture
- Encoder-Decoder (U-Net)
- Skip connections for preserving spatial information
- Sigmoid activation for binary segmentation

---

## 📊 Evaluation Metrics

- **Dice Coefficient**
- **Jaccard Index (IoU)**

### 📈 Results

| Metric | Score |
|--------|------|
| Dice Score | **0.90** |
| IoU Score  | **0.82** |

---

## 📉 Training Curves

- Loss curve shows stable convergence
- Dice & IoU curves show consistent improvement

---

## 🖼️ Results Visualization

- Original MRI Image  
- Ground Truth Mask  
- Predicted Mask  
- Overlay Visualization  

---

## 🚀 Key Features

✔ Accurate tumor segmentation  
✔ Handles class imbalance using Dice Loss  
✔ End-to-end deep learning pipeline  
✔ High performance on test data  

---

## 🧠 Real-World Application

This system can assist:
- Radiologists in detecting tumors faster  
- Hospitals in automating diagnosis workflows  
- Medical AI systems for decision support  

> ⚠️ Note: This model is intended to assist doctors, not replace them.

---

## 📌 How to Run

```bash
# Clone repository
git clone <>

# Install dependencies
pip install -r requirements.txt

# Run notebook / script
