# 🧠 Breast Cancer Detection with PyTorch

A complete beginner-friendly binary classification project built from scratch using **PyTorch**. This project uses the **Breast Cancer Wisconsin Diagnostic Dataset** from Scikit-Learn to train a neural network that predicts whether a tumor is malignant or benign.

---

## 📌 Project Summary

- 🔍 **Goal**: Predict if a tumor is malignant (1) or benign (0)
- 🧱 **Model**: Feedforward Neural Network
- 📊 **Dataset**: Breast Cancer dataset from `sklearn.datasets`
- ⚙️ **Framework**: PyTorch
- 🎯 **Evaluation**: Accuracy on test set

---

## 🚀 Features

✅ Fully built neural network using `nn.Module`  
✅ Proper data preprocessing and normalization  
✅ Training pipeline with `DataLoader`, loss, optimizer  
✅ Model evaluation using accuracy on test data  

---

## 🗂️ Project Structure

```bash
breast-cancer-pytorch/
├── breast_cancer_model.py   # Contains full model code
├── requirements.txt         # Python dependencies
└── README.md                # Project overview

## 📦 Requirements
```bash
torch
scikit-learn
numpy

## Install with:

```bash
pip install torch scikit-learn numpy

## 🧪 How to Run the Project
```bash
# 1. Clone the repo (if needed)
git clone <your-repo-url>
cd breast-cancer-pytorch

# 2. Run the script
python breast_cancer_model.py

## 🧠 Model Architecture
Input: 30 features (from dataset)

Hidden Layer 1: 16 neurons + ReLU

Hidden Layer 2: 8 neurons + ReLU

Output Layer: 1 neuron + Sigmoid (for binary output)

## 📊 Dataset Overview
Total Samples: 569

Features: 30 numerical attributes

Labels: 0 (Benign), 1 (Malignant)

## 👨‍💻 Author
Made with ❤️ by Raju |
