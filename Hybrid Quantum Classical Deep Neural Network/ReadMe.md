# 🌌 Hybrid Quantum-Classical Deep Neural Network on Iris Dataset  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)  
[![PennyLane](https://img.shields.io/badge/PennyLane-Quantum-orange)](https://pennylane.ai/)  


This project demonstrates a **Hybrid Quantum-Classical Deep Neural Network (QCDNN)** built with [PennyLane](https://pennylane.ai/) and [PyTorch](https://pytorch.org/).  
It combines a **variational quantum circuit** with a **classical deep neural layer** for **multi-class classification** on the famous **Iris dataset**.  

---

## 🚀 Features  

✅ **Quantum Layer (4-Qubit System)**  
- Angle encoding of 4 input features.  
- Variational `RY` rotations with trainable parameters.  
- Entanglement via `CNOT` gates.  
- Measurement of **Pauli-Z expectation values**.  

✅ **Classical Neural Network**  
- Single hidden layer with ReLU activation.  
- Output layer → 3 logits for classification.  

✅ **Training & Evaluation**  
- CrossEntropy loss + Adam optimizer.  
- Accuracy tracking, Confusion Matrix, Classification Report.  

---
