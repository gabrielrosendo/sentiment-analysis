# Sentiment Analysis Project

This project develops a sentiment analysis model using logistic regression to classify text as either positive or negative.

## Dataset
The dataset used for this project is from Kaggle: [Sentiment Analysis Dataset](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset?resource=download).

## Problem Statement
The goal of this project is to create a machine learning model that accurately predicts the sentiment of text data, categorizing it as Positive or Negative/Neutral. This sentiment analysis tool is applicable in various domains, such as customer reviews, social media posts, and feedback forms, providing valuable insights into public opinion and aiding decision-making processes.

## Algorithm of the Solution
1. **Data Collection:** Gather text data from the Kaggle dataset.
2. **Data Preprocessing:** Clean the data by converting it to lowercase and removing stop words and punctuation.
3. **Feature Extraction:** Use TF-IDF (Term Frequency-Inverse Document Frequency) to transform the cleaned text into numerical features.
4. **Model Training:** Train a logistic regression model on the processed data to classify sentiment.
5. **Model Evaluation:** Evaluate model performance using a confusion matrix and relevant metrics.
6. **Prediction:** Utilize the trained model to predict sentiment in new text data.

## Analysis of the Findings
The logistic regression model achieved an accuracy of 84%, successfully classifying sentiment in 84% of cases. The confusion matrix indicates that the model correctly identified 3,290 negative sentiments (class 0) and 1,318 positive sentiments (class 1), with 502 and 387 misclassifications, respectively.

The classification report reveals strong performance for negative sentiment classification (precision: 0.89, recall: 0.87), while positive sentiment classification shows lower precision (0.72) and recall (0.77), indicating potential for improvement. The weighted average f1-score of 0.84 reflects balanced performance across both classes.

Example predictions show the model's capability to distinguish between positive, neutral, and negative sentiments. However, it struggles with mixed sentiments, highlighting the need for further tuning and advanced natural language processing techniques.

## Conclusion
This sentiment analysis project effectively classifies text data using a logistic regression model, achieving 84% accuracy. While suitable for applications such as product reviews and social media monitoring, further enhancements are needed to better handle mixed sentiments and complex phrases.

**References**
- https://www.geeksforgeeks.org/python-linear-regression-using-sklearn/
- https://scikit-learn.org/1.5/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html
