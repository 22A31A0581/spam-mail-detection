# spam-mail-detection
📘 Project Overview

This project detects whether an email is Spam or Ham (Not Spam) using Machine Learning and Natural Language Processing (NLP) techniques.
The model is trained on a dataset of labeled emails and uses TF-IDF vectorization with Logistic Regression for classification.


🚀 Technologies Used:

Python – Programming language
Google Colab – Development and model training environment
pandas, NumPy – Data handling and preprocessing
scikit-learn – ML library for feature extraction and model building
TfidfVectorizer for text feature extraction
LogisticRegression for classification
NLP Techniques – Text cleaning, tokenization, TF-IDF
Matplotlib / Seaborn (optional) – For visualizations

Machine Learning Workflow:

Data Collection – Load email dataset (e.g., mail_data.csv)
Data Preprocessing
Handle missing values
Clean text (remove symbols, stopwords, lowercase)
Feature Extraction – Convert text into numerical form using TF-IDF
Model Training – Train a Logistic Regression model
Model Evaluation – Test accuracy, precision, recall, and F1-score
Prediction – Classify new/unseen emails as Spam or Ham


