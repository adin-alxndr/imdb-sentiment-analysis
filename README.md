# IMDB Sentiment Analysis

## 📌 Project Overview
This project focuses on performing sentiment analysis on IMDB movie reviews to classify them into positive and negative categories.

By understanding the sentiment expressed in reviews, businesses and movie platforms can identify what customers like or dislike, improving recommendations and marketing strategies.

---

## 🎯 Objective
- Classify movie reviews as positive or negative based on textual content.
- Identify the most influential words driving positive and negative sentiments.
- Extract actionable business insights from customer feedback.

---

## 📊 Dataset
**Source:** IMDB via Hugging Face Datasets
**Row (train split):** 25,000  
**Columns:** 2  
**Target Variable:** `Sentiment` (positive or negative)

Each row represents a movie review and its sentiment label. The text data contains real-world reviews, including slang, punctuation, typos, and varying lengths.

---

## 🧠 Methodology
1. Data Loading – Load IMDB dataset and convert to pandas DataFrame.
2. Data Cleaning  
   - Remove duplicates and missing values
   - Normalize text: lowercase, remove punctuation, remove stopwords, stemming
3. Exploratory Data Analysis (EDA)  
   - Review length and word count analysis
   - Sentiment distribution
   -  Most common words and word clouds
4. Feature Engineering  
   – TF-IDF vectorization with unigrams and bigrams
5. Model Training  
   - Logistic Regression  
   - Naive Bayes
   - Cross-validation with ROC-AUC
6. Model Evaluation  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - ROC-AUC  
7. Top Keywords & Business Insights – Identify words most associated with positive and negative reviews.
8. Conclusion – Summarize model performance and recommendations.

---

## ⚙️ Tools & Libraries
- **Python**
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- VSCode 
- GitHub  

---

## 📈 Model Performance

### Logistic Regression
- Accuracy: **0.87**
- Weighted F1-score: **0.87**
- 
### Random Forest
- Accuracy: **0.86**
- Weighted F1-score: **0.86**

**Best model:** Logistic Regression
It provides better overall performance and is interpretable for identifying influential words.

---

## 🔍 Top Keywords Influencing Sentiment
Positive reviews: great, excel, perfect, enjoy, love, favorite, best, amazing, beautiful, brilliant
Negative reviews: worst, bad, waste, awful, bore, disappoint, fail, poor, nothing, worse

---

## 💡 Business Insights
- Focus marketing on features and aspects that customers highlight positively.
- Address issues raised in negative reviews to improve product/service quality.
- Monitor sentiment trends to detect dissatisfaction early.

---

## 📝 Business Recommendations
- Highlight positive aspects in marketing campaigns.
- Improve services or features associated with negative keywords.
- Collect ongoing feedback to track changes in customer sentiment.

---

## 🚀 Future Improvements
- Handle class imbalance with techniques like SMOTE or class weighting.
- Perform hyperparameter tuning for better model performance.
- Experiment with advanced models such as XGBoost or BERT-based classifiers.
- Deploy model using Streamlit, FastAPI, or a web dashboard for real-time sentiment monitoring.

---

## 👤 Author
Name: adin_alxndr

---

## 📎 License
This project is for educational and portfolio purposes only.
