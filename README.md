# Assignment 2 - Text Analytics (Sentiment Analysis)

---

## (1) Problem Statement
The problem is to analyze public sentiment on tweets related to World War 3 discussions. The goal is to classify tweets into positive, negative, and neutral sentiments using machine learning techniques.

---

## (2) Objective
- To collect tweets related to World War 3 discussions  
- To preprocess and clean textual data  
- To classify tweets into positive, negative, and neutral sentiments  
- To apply machine learning models for sentiment analysis  
- To evaluate model performance using precision and recall  

---

## (3) Dataset
- Source: Tweets collected manually from Twitter (X) using keywords like "World War 3", "WW3", and "global conflict"  
- Features:
  - tweet_id  
  - tweet_text  
  - sentiment (positive, negative, neutral)  
- Size: 100 tweets  

---

## (4) Methodology
1. **Data Preprocessing**  
   - Converted text to lowercase  
   - Removed URLs, mentions, punctuation, and special characters  
   - Removed extra spaces  

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed sentiment distribution using visualization  

3. **Model Building**  
   - Applied TF-IDF vectorization  
   - Trained the following models:
     - Naive Bayes  
     - Support Vector Machine (SVM)  
     - Logistic Regression  

4. **Evaluation**  
   - Evaluated models using:
     - Precision  
     - Recall  
     - Accuracy  

---

## (5) Results
- All models achieved perfect scores:
  - Precision = 1.00  
  - Recall = 1.00  
  - Accuracy = 1.00  

- Insight:
  - The dataset is small and contains clearly distinguishable sentiment patterns, leading to perfect classification performance.  
  - In real-world scenarios, performance may vary with more complex datasets.  

---
## Conclusion
Sentiment analysis was successfully performed on tweets related to World War 3 discussions. All models performed equally well, achieving perfect accuracy. However, larger and more complex datasets are required for realistic performance evaluation.

## Student's details -
Name:Ansari Jafeera 
- Roll No:03
- UIN:231A022
-YEAR: TE-AIDS

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook




