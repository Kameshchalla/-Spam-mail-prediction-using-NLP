# 📧 Spam Mail Prediction using Logistic Regression

## 📝 Project Overview

This project demonstrates a **Spam Mail Prediction** system using **Logistic Regression**. The objective is to classify email messages as either **Spam** or **Not Spam** based on their content.

The system uses **Natural Language Processing (NLP)** techniques to convert textual data into numerical vectors for model training and evaluation.

---

## 🔄 Project Workflow

1. **Load the Data**
2. **Encode Labels**
   - `spam` → `0`
   - `ham` → `1`
3. **Data Splitting**
   - Split the dataset into **training** and **testing** sets
4. **Feature Extraction**
   - Use **TF-IDF Vectorization** to convert email text into numerical vectors
5. **Model Training**
   - Train a **Logistic Regression** model on the training data
6. **Model Evaluation**
   - Evaluate the model on both training and testing datasets
7. **Prediction System**
   - Build a system to classify new emails as **Spam** or **Not Spam**

---

## 🛠️ Libraries Used

- [pandas](https://pandas.pydata.org/) – Data manipulation and analysis  
- [numpy](https://numpy.org/) – Numerical computations  
- [scikit-learn](https://scikit-learn.org/) – Machine learning models and tools  

---

## 📊 Model Performance

- **Accuracy on Training Data:** 97.24%  
- **Accuracy on Testing Data:** 96.86%

---

## 🚀 Features

- Lightweight and efficient spam classification
- Built using simple, interpretable machine learning techniques
- Easy to extend or integrate into other systems

---

## 📂 Project Structure


    scikit-learn - for machine learning containig the complete code for project
Model Performance:
  Accuracy on Training Data : 97.24%
  Accuracy on Testing Data : 96.86%
