# 📊 Twitter Sentiment Analysis Using NLP

## 📌 Project Overview
This project performs **sentiment analysis on Twitter data** using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
Tweets are classified into **Positive**, **Neutral**, and **Negative** sentiments.

This project was completed as part of the **OASIS INFOBYTE – Data Analytics Internship (Level 1)**.

---

## 🎯 Objective
- Analyze public sentiment from Twitter data  
- Clean and preprocess unstructured text data  
- Convert text data into numerical features using TF-IDF  
- Build and evaluate a machine learning model for sentiment classification  

---

## 📁 Dataset
- **Source:** Public Twitter sentiment dataset  
- **Total Records:** 162,980 tweets  
- **Columns:**
  - `clean_text` – Tweet text  
  - `category` – Sentiment label  
    - `-1` → Negative  
    - `0` → Neutral  
    - `1` → Positive  

Missing sentiment labels were removed during data cleaning.

---

## 🛠️ Tools & Technologies
- Python  
- Google Colab  
- Pandas & NumPy  
- NLTK  
- Scikit-learn  
- Matplotlib  

---

## ⚙️ Methodology
1. Loaded dataset from Google Drive in Google Colab  
2. Removed records with missing sentiment labels  
3. Performed text preprocessing:
   - Lowercasing
   - Removing punctuation and special characters
   - Stopword removal
   - Lemmatization  
4. Extracted features using **TF-IDF (unigrams + bigrams)**  
5. Trained a **Logistic Regression** model with balanced class weights  
6. Evaluated the model using accuracy score, classification report, and confusion matrix  
7. Visualized sentiment distribution  

---

## 📈 Results
- **Model Used:** Logistic Regression  
- **Accuracy Achieved:** ~68–70%  
- Positive sentiment classification performed best  
- Improved performance compared to baseline Naive Bayes model  

---

## 📊 Visualizations
- Confusion Matrix  
- Sentiment Distribution Bar Chart  

---

## 🧠 Key Learnings
- Importance of text preprocessing in NLP tasks  
- Effect of feature engineering on model accuracy  
- Challenges of sentiment analysis on noisy social media data  

---

## 🚀 Future Improvements
- Apply advanced NLP models like BERT  
- Handle class imbalance using advanced resampling techniques  
- Perform hyperparameter tuning  

---

## 👤 Author
**Narayan**  
Data Analytics Intern – OASIS INFOBYTE  
