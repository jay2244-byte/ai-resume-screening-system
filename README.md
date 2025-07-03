# 🤖 AI-Powered Resume Screening System

This project demonstrates a Machine Learning-based system to automatically classify resumes into job categories like Data Scientist, Software Developer, etc., using NLP techniques and Responsible AI (LIME) for explainability. The implementation is done in Google Colab.

## 🚀 Features
- Resume text preprocessing with TF-IDF
- Classification using Multinomial Naive Bayes
- Responsible AI with LIME to explain predictions
- Supports resume screening automation

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas
- LIME (for model interpretability)
- Google Colab

## 📁 Files
- `resume_classifier.ipynb`: Main Colab notebook with code
- `sample_resumes/`: Folder with sample resumes (text)
- `lime_explanations/`: Sample LIME output for explainability

## 📌 Steps to Run
1. Open the notebook in Google Colab
2. Upload or load your dataset
3. Train the classifier
4. Predict resume category
5. Use LIME to visualize the most influential words

## 📊 Responsible AI
We use LIME (Local Interpretable Model-Agnostic Explanations) to provide transparency in AI decisions and ensure ethical screening.

## 📷 Sample Output
![LIME Explanation](lime_explanations/example_explanation.html)

## 📜 License
This project is for educational and non-commercial use only.

---
