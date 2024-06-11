# Fake News Detection Project
## Overview
* This project aims to detect fake news using machine learning techniques. It involves the classification of news articles into either real or fake categories based on their content.

## Dataset
The dataset used consists of two main sources:

* True News: Contains genuine news articles.
* Fake News: Comprises fabricated or misleading articles.
## Preprocessing
The dataset preprocessing steps involve:

* Labeling data: True news labeled as 0, fake news labeled as 1.
* Cleaning data: Text data was converted to lowercase, special characters removed, lemmatization applied, and stop words removed.
## Dataset Analysis
* Checked for null values (no nulls found).
* Examined dataset balance: Balanced with similar proportions of true and fake news articles.
## Model Training
### Feature Extraction
* Used TF-IDF Vectorization: Converted text data into numerical features using TF-IDF vectorizer with 50,000 maximum features and considering unigrams and bigrams.
## Model Selection
* Employed Multinomial Naive Bayes classifier for its effectiveness with text data.
## Training and Evaluation
* Split dataset into train and test sets (80/20).
* Trained the model on the training set and evaluated performance on the test set.
* Obtained classification reports and accuracy scores for both test and train sets.
## Results
* Achieved accuracy scores on both train and test sets.
* Classification reports showcase precision, recall, and F1-score for each class.
## Conclusion
The Multinomial Naive Bayes model demonstrated reasonable accuracy in detecting fake news based on the provided dataset and features.

## Instructions to Run
1. Ensure necessary Python libraries are installed (e.g., pandas, numpy, scikit-learn, nltk).
2. Run the provided Python script after adjusting the file paths if needed.
