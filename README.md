# fake-news-detection-ml

# Fake News Detection using Machine Learning

This project classifies news articles as fake or real using traditional machine learning models. The dataset includes labeled news from two sources: Fake.csv and True.csv.

## Dataset

- *Fake.csv*: Contains fake news articles.
- *True.csv*: Contains real news articles.
- Merged and labeled as binary classification problem.

## Workflow

- Preprocessing: text cleaning, combining title and text
- Feature Extraction: TF-IDF
- Models Used:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
- Evaluation:
  - Accuracy, Precision, Recall, F1
  - Confusion Matrix & ROC Curve
