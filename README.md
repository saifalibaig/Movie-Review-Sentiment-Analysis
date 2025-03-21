# 🎬 Movie Review Sentiment Analysis

This project focuses on performing sentiment analysis on movie reviews using machine learning models. The goal is to classify reviews as **positive** or **negative**, based on the review text.

---

## 📂 Dataset

The dataset used is the [IMDb Movie Review Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) which contains 50,000 labeled movie reviews:

- 25,000 positive reviews
- 25,000 negative reviews  
- The dataset is split evenly into training and testing sets (80:20 used here).

---

## 🧹 Preprocessing

The following steps were applied to clean and prepare the data:

- Lowercasing the text
- Removing HTML tags, punctuation, and numbers
- Tokenization using `re` (regex)
- Stopword removal using `sklearn`'s English stopword list
- Vectorization with **TF-IDF**

*Note:* NLTK is not used to avoid environment-specific issues.

---

## ⚙️ Models Implemented

Three classification models were trained and evaluated:

- **Logistic Regression**
- **Multinomial Naive Bayes**
- **Support Vector Machine (SVM)**

---


## 📊 Evaluation Results

### ✅ Logistic Regression (Best)
- **Accuracy:** 88.40%
- **F1 Score:** 0.8868


---

### 🧠 Naive Bayes
- **Accuracy:** 84.77%
- **F1 Score:** 0.8492


---

### 📈 Support Vector Machine (SVM)
- **Accuracy:** 87.26%
- **F1 Score:** 0.8751


---

## 🧠 Conclusion

- **Logistic Regression** performed the best across all metrics.
- **Naive Bayes** was the fastest but least accurate.
- **SVM** provided a solid balance between performance and training time.

---

## 🚀 Future Work

- Implement deep learning models (e.g., LSTM, BERT)
- Hyperparameter tuning with GridSearchCV
- Create a web interface using Flask or Streamlit
- Explore multiclass or sentiment intensity classification

---

## 📁 Files Included

- `Movie_Review_Sentiment_Analysis_.ipynb`: Jupyter notebook with all steps
- Dataset (IMDB): Download separately [here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)


