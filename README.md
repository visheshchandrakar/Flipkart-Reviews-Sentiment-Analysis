# Flipkart-Reviews-Sentiment-Analysis

Flipkart Reviews Sentiment Analysis

Goal of the Project

The objective of this project is to perform Sentiment Analysis on Flipkart Reviews to classify customer sentiments as positive, negative, or neutral. The analysis aims to understand customer feedback, identify key trends, and gain insights into product performance and customer satisfaction.

This project involves data preprocessing, exploratory data analysis (EDA), sentiment classification using machine learning models, and visualization of results.

Approach

1. Data Collection and Cleaning

The dataset consists of Flipkart customer reviews, including text feedback and ratings. The preprocessing steps include:

Removing special characters, punctuation, and stopwords.

Converting text to lowercase for uniformity.

Tokenization and Lemmatization for better text processing.

Handling missing values and duplicate records.

2. Exploratory Data Analysis (EDA)

EDA was conducted to understand the dataset characteristics:

Distribution of ratings.

Common words and phrases in positive and negative reviews.

Word cloud visualization for frequently used terms.

3. Sentiment Classification

The sentiment analysis was performed using the following models:

Rule-Based Sentiment Analysis (VADER for text polarity analysis).

Machine Learning Models:

Logistic Regression

Naïve Bayes Classifier

Support Vector Machines (SVM)

Random Forest Classifier

Model performance was evaluated using accuracy, precision, recall, and F1-score.

4. Visualization of Results

The sentiment distribution and classification results were visualized using:

Bar charts for sentiment category distribution.

Confusion matrices for model performance comparison.

Word clouds for top keywords in positive and negative sentiments.

Tools and Technologies Used

Python - For data preprocessing, machine learning, and visualization.

Libraries:

pandas, numpy - Data handling and manipulation.

nltk, textblob - Natural Language Processing (NLP).

matplotlib, seaborn, wordcloud - Data visualization.

scikit-learn - Machine learning model implementation.

Datasets Used

The dataset used includes Flipkart product reviews, containing:

Review text

Customer ratings

Metadata on product and review timestamps

Built With

Python 3.8.2

Jupyter Notebook

Authors

Your Name
