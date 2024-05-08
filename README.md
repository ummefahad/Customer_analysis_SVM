##**Customer Review Sentiment Analysis**
This project focuses on analyzing sentiment in customer reviews using machine learning techniques. The dataset used contains reviews from an e-commerce website, including information such as clothing ID, age, review text, rating, and more.

**Dataset**
The dataset used for this analysis is "Womens Clothing E-Commerce Reviews.csv". It contains the following columns:

Unnamed: 0
Clothing ID
Age
Title
Review Text
Rating
Recommended IND
Positive Feedback Count
Division Name
Department Name
Class Name
**Analysis Steps**
**Data Cleaning:**
Removed rows with missing review text.
Checked for missing values in other columns.
**Exploratory Data Analysis (EDA):**
Checked the distribution of ratings using a countplot.
**Sentiment Analysis:**
Utilized TextBlob to categorize reviews into positive, neutral, and negative sentiments based on polarity scores.
**Text Preprocessing:**
Performed tokenization, stop words removal, and lemmatization on the review text using NLTK.
**Document Embeddings:**
Calculated document embeddings using Word2Vec word vectors.
**Machine Learning Models:**
Trained Support Vector Machine (SVM) and Logistic Regression classifiers to predict sentiment.
Evaluated models using accuracy scores.
**Results**
SVM Classifier Accuracy: Insert accuracy here
Logistic Regression Classifier Accuracy: Insert accuracy here
**Files**
README.md: This file, providing an overview of the project.
Womens Clothing E-Commerce Reviews.csv: The dataset used for analysis.
customer_review_sentiment_analysis.ipynb: Jupyter Notebook containing the Python code for analysis.
Dependencies
pandas
numpy
seaborn
nltk
scikit-learn
textblob
