
# 📧 Email Spam Classification using NLP & Machine Learning

This project aims to build a machine learning model that classifies emails as **Spam** or **Ham** using natural language processing (NLP) techniques like Bag of Words and TF-IDF, followed by classification using the **Naive Bayes algorithm**.


## Dataset

- **Source:** [Kaggle - Email Spam Classification Dataset](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)
- Contains labeled email messages with two classes:
  - `Spam`
  - `Ham` (Non-spam)


## 🧹 Data Preprocessing

Steps performed:
- Removed special characters and extra spaces
- Lowercased all text
- Removed stopwords 
- Converted text into numerical form using:
  - **Bag of Words (BoW)**
  - **TF-IDF (Term Frequency-Inverse Document Frequency)**


## 🧠 Model Building

- **Training/Testing Split:** Used `train_test_split` to divide data
- **Classifier:** Multinomial Naive Bayes
- **Metrics Evaluated:**
  - Accuracy
  - **Precision Score**
  - Confusion Matrix 


## Libraries Used
python ,
pandas ,
numpy ,
sklearn , 
nltk

