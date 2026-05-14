# 🛡️ Content Moderation Classifier (DistilBERT Fine-Tuning)

## 📌 Overview

This project implements a **Transformer-based NLP model** for detecting toxic and non-toxic content using **DistilBERT fine-tuning**.

It is inspired by real-world content moderation systems used in platforms like **Meta, YouTube, and Reddit**, where large-scale AI models are used to filter unsafe user-generated content.

The model is trained on the **Jigsaw Toxic Comment Classification Dataset**, which contains ~160,000 real Wikipedia comments labeled for toxicity.

---

## 🎯 Objective

The goal of this project is to:

- Classify text as **toxic or non-toxic**
- Demonstrate fine-tuning of transformer models for NLP tasks
- Work with real-world noisy text data
- Build a foundational NLP moderation system

---

## 🧠 Model Information

- Base Model: **DistilBERT (Hugging Face Transformers)**
- Task: Binary Text Classification
- Architecture: Transformer encoder + classification head
- Framework: PyTorch / PyTorch Lightning

---

## 📊 Dataset

- **Jigsaw Toxic Comment Classification Dataset**
- ~160,000 labeled Wikipedia comments
- Labels:
  - Toxic
  - Non-Toxic

---

## ⚙️ Tech Stack

- Python 🐍
- PyTorch ⚡
- PyTorch Lightning
- Hugging Face Transformers 🤗
- Pandas, NumPy
- Jupyter Notebook / Python scripts

---


---

## 📈 Current Status

- ✔ Dataset preprocessing completed  
- ✔ DistilBERT fine-tuning implemented  
- ✔ Training pipeline created  
- ✔ Basic inference pipeline available  
- ⏳ Deployment (API/UI) not implemented yet  

---

## 💡 Key Learnings

- Transformer-based NLP fine-tuning
- Handling real-world noisy datasets
- Binary text classification pipeline
- Model training and evaluation using PyTorch ecosystem

---


## 🔮 Future Improvements

- Deploy model using FastAPI
- Build real-time moderation web app
- Add multi-class toxicity detection (hate, spam, abuse)
- Optimize inference using ONNX/TorchScript
- Add UI dashboard for predictions

---

