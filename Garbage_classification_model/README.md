# 🗑️ Garbage Classification using ResNet50 (Kaggle Dataset)

A deep learning project that classifies different types of waste material using **Transfer Learning** with ResNet50. This model helps in automating waste segregation — a valuable step towards smart waste management systems and environmental sustainability. 🌱

---

## ✨ Features
✔️ Uses **ResNet50** pre-trained on ImageNet  
✔️ Supports **multiple waste categories**  
✔️ Includes **data augmentation**  
✔️ Handles **class imbalance** with undersampling  
✔️ Achieves high accuracy with optimized training

---

## 🧠 Workflow
1️⃣ Data Loading & Preprocessing  
2️⃣ Dataset Balancing (UnderSampling)  
3️⃣ Model Architecture Setup (ResNet50 + Custom Layers)  
4️⃣ Model Training  
5️⃣ Validation & Evaluation  
6️⃣ Save and Use Model for Predictions

---

## 💼 Dataset
Dataset Source: Kaggle  
Contains images of waste materials like:
- Battery
- Biological
- Brown Glass
- Cardboard
- Clothes
- Green Glass
- Metal
- Paper
- Plastic
- Shoes
- Trash
- White Glass

Images are resized to **128×128** with **RGB mode**.

---

## 🔧 Tech Stack
| Component | Used |
|----------|------|
| Language | Python |
| Deep Learning Framework | TensorFlow / Keras |
| Pretrained Model | ResNet50 |
| Visualization | Matplotlib |
| Data Handling | Pandas, NumPy |
| Dataset Balancing | imblearn |

---

## 🏗️ Project Structure
```bash
📁 Garbage-Classification-ResNet50/
│── 📄 model_training.ipynb
│── 📄 README.md
│── 📄 requirements.txt
│── 📁 saved_model/   # auto-created after training
│── 📁 data/          # contains dataset images
