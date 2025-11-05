# Pancreatic_Cancer_Detection_ML
Machine learning–based classification of plasma samples using PESI-MS data to detect pancreatic cancer. Evaluated SVM, Random Forest, and Deep Neural Network models.
# 🧠 Machine Learning Applied to Detect Pancreatic Cancer

This repository contains my MSc Data Science dissertation project at **Liverpool John Moores University (2023)**.  
The research explored how **machine learning algorithms** can be used with **Probe Electrospray Ionization Mass Spectrometry (PESI-MS)** data to detect pancreatic cancer at an early stage.

---

## 📘 Project Overview
- Compared three machine learning models:
  - **Support Vector Machine (SVM)**
  - **Random Forest Classifier (RFC)**
  - **Deep Neural Network (DNN)**
- Used plasma sample data from the **UK Biobank** (positive & negative ion modes).
- Pre-processing included:
  - Missing-value imputation  
  - Recursive Feature Elimination (RFE)  
  - Data scaling and cross-validation  

---

## 📊 Results
| Model | Accuracy | Key Strength |
|--------|-----------|--------------|
| **SVM** | **0.75** | Best overall performance |
| **RFC** | 0.65 | Good at healthy-sample recognition |
| **DNN** | 0.55 | Needs further optimization |

SVM achieved the most reliable classification of pancreatic cancer (PDAC) and healthy cases.

---

## 🧰 Tools & Libraries
Python • Pandas • NumPy • Scikit-learn • TensorFlow • Matplotlib • Google Colab

---

## 🧩 Future Work
- Increase dataset size and include age, gender, and ethnicity features  
- Improve DNN architecture with hyper-parameter tuning  
- Apply ensemble techniques and real-world validation  

---

## 📄 Files
- `Dissertation_final.pdf` – full academic report    

---

## ✍️ Author
**Dhanushka Francisku**  
🎓 MSc Data Science, Liverpool John Moores University  
📍 London, UK  
📧 [frensiskul@gmail.com](mailto:frensiskul@gmail.com)  
🔗 [LinkedIn](www.linkedin.com/in/dhanushka-francisku-244683202)
