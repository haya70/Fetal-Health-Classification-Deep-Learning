# Fetal Health Classification using Neural Networks 🧬🤖

## 📌 Overview
This project leverages **Artificial Intelligence** and **Deep Learning** techniques to assist medical professionals in monitoring fetal health. Using Cardiotocogram (CTG) exam data, I built a Multi-Layer Perceptron (MLP) model to classify fetal health status into three distinct categories:
1. **Normal**
2. **Suspect**
3. **Pathological**

This project was developed as part of the **GDG AI Bootcamp at Shaqra University**.

## 📊 Dataset
The dataset consists of **2,126 records** of features extracted from Cardiotocogram exams.
- **Source:** [Fetal Health Classification Dataset on Kaggle]
- **Features:** 21 attributes including baseline heart rate, fetal movements, and uterine contractions.

## 🛠️ Methodology
To ensure high performance and reliability, the following pipeline was implemented:

1. **Data Preprocessing:** - Handled missing values and performed exploratory data analysis (EDA).
   - Applied **StandardScaler** to normalize features for better Neural Network convergence.
   
2. **Model Architecture:**
   - Used `MLPClassifier` from Scikit-Learn.
   - **Architecture:** Input Layer -> Hidden Layer (64 neurons) -> Hidden Layer (32 neurons) -> Output Layer.
   - **Activation Function:** ReLU.
   - **Optimizer:** Adam.

3. **Training & Evaluation:**
   - Split data into Training, Validation, and Test sets.
   - Utilized Early Stopping to prevent overfitting.

## 📈 Results
The model achieved strong performance metrics on unseen test data:

- **Test Accuracy:** **87.09%** ✅
- **Precision (Normal Class):** 91%
- **Recall (Normal Class):** 97%

*(See the `notebook` for the detailed Confusion Matrix and Learning Curves).*

## 💻 Technologies Used
- **Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.
- **Environment:** Jupyter Notebook / Google Colab.

## 🚀 Future Work
- Plan to experiment with other Deep Learning architectures (like CNNs) for potentially higher accuracy.
- Deploy the model as a web application using Streamlit.

---
*Developed by [Haya Almutlaq]*
