# 💬 Sentiment Analysis using NLP (Project 2)

### **Objective**
To build an automated system for classifying public opinion from social media text, demonstrating expertise in Natural Language Processing (NLP) and multi-class classification.

### **Methodology and Key Results**
* **Data Preparation:** Cleaned noisy Twitter data by removing URLs, mentions, and stopwords.
* **Feature Engineering:** Converted the cleaned text into numerical features using **TF-IDF Vectorization**.
* **Best Model:** **Multinomial Naive Bayes (MNB) Classifier** was selected over Random Forest.
* **Performance:** Achieved a strong **Macro F1-Score of 0.6995**, indicating balanced prediction performance across all three classes (Positive, Negative, and Neutral).

### **Deployment Readiness**
The final, optimized MNB model was saved as a `.pkl` file, confirming the solution is ready to be deployed as an efficient text-scoring API service.
