# 🎥**Sentiment Analysis on IMDB Movie Reviews**

## 📌 **Project Overview**
This project applies **sentiment analysis** to the IMDB movie reviews dataset to classify reviews as **positive** or **negative**. The goal is to explore the dataset, preprocess the textual data, build multiple machine learning models, and evaluate their performance using several metrics.  
The analysis follows a complete **data analytics pipeline** — from **data preprocessing** to **exploratory data analysis (EDA)**, **model training**, and **performance comparison**.  

---

## 📊 **Dataset**
- **Source:** IMDB movie review dataset  
- **Size:** 40,000 samples  
- **Attributes:**
  | Attribute | Description |
  |-----------|-------------|
  | `text` | The movie review text |
  | `label` | Sentiment label (`0` = Negative, `1` = Positive) |
The dataset is **balanced**, with nearly equal proportions of positive and negative reviews.  

---

## 🎯 **Objectives**  
- Perform **sentiment analysis** on IMDB movie ratings.  
- Conduct **exploratory data analysis (EDA)** to gain insights into text length and word frequencies.  
- Implement and compare multiple **classification models**:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Naïve Bayes  
- Evaluate performance using:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - AUC-ROC Score  
  - Confusion Matrix  
  - ROC Curve  

---

## 🛠️ **Methodology** 
### 1️⃣ **Data Preprocessing**
- Checked for missing and duplicate rows (removed 277 duplicates).  
- Converted text to lowercase.  
- Removed punctuation, stopwords, and applied stemming.  
- Applied **TF-IDF Vectorization** to transform text into numerical features.  

### 2️⃣ **Exploratory Data Analysis (EDA)**
- Visualized label distribution using **pie charts** and **bar plots**.  
- Analyzed average text length per sentiment using **box plots**.  
- Generated **word clouds** to identify most frequent positive and negative words.  

### 3️⃣ **Model Training & Evaluation**
- Split data into **80% training** and **20% testing** sets.  
- Implemented four machine learning classifiers.  
- Computed evaluation metrics and visualized results:  
  - Confusion matrices  
  - ROC curves  
  - Heatmap comparison of metrics  

---

## 📈 **Results** 
**Logistic Regression** achieved the highest performance across all metrics and is recommended as the best model for this dataset.

---

## 📊 **Visualizations** 
- **Word Clouds:** Show most frequent positive and negative words.  
- **ROC Curves:** Compare model ability to distinguish between classes.  
- **Heatmap:** Displays performance metrics across models for easier comparison.  
- **Confusion Matrices:** Show distribution of predictions (TP, FP, TN, FN).  

---

📌 **Conclusion**
- Logistic Regression provided the most accurate and reliable sentiment classification model.
- EDA revealed that positive reviews tend to be slightly longer than negative ones.
- The dataset was well-balanced, eliminating the need for resampling techniques.

---

## 📜 **License**
This project is for educational purposes under NMJ40203 - Data Analytics coursework.
You may modify and use this project for learning, but proper credit to the author is appreciated.
