# Sentiment Analysis Using Machine Learning

## 📌 Project Overview

This project performs **Sentiment Analysis** on airline customer tweets using Machine Learning.

The system classifies customer tweets into three sentiment categories:

* 😊 Positive
* 😐 Neutral
* 😞 Negative

The project uses text preprocessing, TF-IDF feature extraction, and two Machine Learning algorithms:

* Naive Bayes
* Logistic Regression

The models are evaluated using Accuracy, Precision, Recall, F1-score, Classification Report, and Confusion Matrix.

---

## 🎯 Objective

The main objective of this project is to analyze customer opinions from Twitter data and automatically classify each tweet as Positive, Neutral, or Negative.

This can help organizations understand customer feedback and identify areas that need improvement.

---

## 📊 Dataset

**Dataset:** Twitter US Airline Sentiment

The dataset contains tweets from customers about different US airlines.

### Sentiment Classes

| Sentiment | Description                     |
| --------- | ------------------------------- |
| Positive  | Customer has a positive opinion |
| Neutral   | Customer has a neutral opinion  |
| Negative  | Customer has a negative opinion |

The dataset was obtained from Kaggle.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* WordCloud
* Joblib
* TF-IDF

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading & Inspection
   ↓
Text Preprocessing
   ↓
Lowercase Conversion
   ↓
URL / Mention / Punctuation Removal
   ↓
Tokenization
   ↓
Stopword Removal
   ↓
Train-Test Split
   ↓
TF-IDF Feature Extraction
   ↓
Machine Learning Models
   ↓
Naive Bayes
   ↓
Logistic Regression
   ↓
Model Evaluation
   ↓
Error Analysis
   ↓
Best Model Selection
   ↓
New Sentence Prediction
```

---

## 🧹 Text Preprocessing

The following preprocessing techniques were applied:

* Converted text to lowercase
* Removed URLs
* Removed mentions
* Removed punctuation
* Tokenized text
* Removed stopwords
* Prepared clean text for Machine Learning

---

## 🔢 Feature Extraction

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert text data into numerical features that Machine Learning algorithms can understand.

The TF-IDF representation gives importance to words based on their frequency in the document and across the dataset.

---

## 🤖 Machine Learning Models

### 1. Naive Bayes

Naive Bayes is a probabilistic Machine Learning algorithm commonly used for text classification.

It predicts the sentiment category based on the probability of words appearing in each sentiment class.

### 2. Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for classification.

In this project, it is used to classify tweets into Positive, Neutral, and Negative sentiment categories.

---

## 📈 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report
* Confusion Matrix

The performance of Naive Bayes and Logistic Regression was compared to identify the better-performing model.

---

## 📊 Visualizations

The project includes the following visualizations:

* Sentiment Distribution
* Confusion Matrix for Naive Bayes
* Confusion Matrix for Logistic Regression
* Positive WordCloud
* Negative WordCloud
* Neutral WordCloud

These visualizations help understand the dataset and model performance.

---

## 🔍 Error Analysis

Misclassified tweets were analyzed to understand why the models made incorrect predictions.

Five misclassified examples were examined to identify possible reasons such as:

* Ambiguous language
* Short text
* Negation
* Informal language
* Sarcasm
* Context-dependent words

---

## 🧪 New Sentence Prediction

The trained model can also predict the sentiment of a new sentence provided by the user.

Example:

```text
"I had an amazing experience with the airline."
```

Possible prediction:

```text
Positive
```

---

## 💾 Saved Files

The project also saves the trained Machine Learning model and TF-IDF vectorizer for future predictions.

```text
sentiment_model.pkl
tfidf_vectorizer.pkl
processed_dataset.csv
```

---

## 📁 Project Structure

```text
sentiment-analysis-project/
│
├── Sentiment_Analysis.ipynb
├── dataset.csv
├── processed_dataset.csv
├── sentiment_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
└── requirements.txt
```

> File names may vary depending on the final project files uploaded to the repository.

---

## ✅ Conclusion

This project demonstrates how Machine Learning and Natural Language Processing can be used to perform three-class sentiment classification.

The project successfully processes customer tweets, converts text into numerical features using TF-IDF, trains Naive Bayes and Logistic Regression models, evaluates their performance, performs error analysis, and predicts the sentiment of new sentences.

Sentiment analysis can be useful for businesses to understand customer opinions and improve their products and services.

---

## 👩‍💻 Author

**Gayatri Datir**

MCA Student
Interested in Data Analytics, Machine Learning and Python.
