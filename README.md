## What

Financial sentiment analysis using Machine Learning

## Why

In today's financial landscape, access to timely and meaningful information is vital for making well-informed decisions. This project focuses on using supervised Machine Learning methods to systematically analyze sentiments in financial texts. The project encompasses data preprocessing, feature selection, model training, and evaluation.

## Data Overview and Preprocessing

The dataset consists of headlines from financial articles labeled as positive, neutral, or negative sentiments. Preprocessing steps include tokenization, stemming, punctuation and stop word removal, and binary classification of sentiments. The dataset is balanced using oversampling and split into training and test sets with 80-20 ratio.

## Feature Selection

Feature engineering involves Bag of Words (BoW) and TF-IDF representations to convert textual data into numerical format for ML models. Custom stop words specific to financial headlines are used to enhance feature selection.

## Methods

Two models are evaluated: Multinomial Naive Bayes (NB) and Logistic Regression (LR). Logistic loss function is used for both models due to its suitability for binary classification tasks.

## Model Evaluation & Conclusion

Models are evaluated for accuracy, precision, recall, and F1-score using oversampling and k-fold cross-validation techniques. LR with Count Vectorization and k-folding yields the highest accuracy and F1-score. Further improvements could be explored through diverse data collection and advanced feature engineering techniques.

## Results

Check the SentimentAnalysis.pdf