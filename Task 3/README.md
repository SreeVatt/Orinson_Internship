# Task 3: Sentiment Analysis on Movie Reviews

This repository implements sentiment analysis on movie reviews to classify them as positive or negative.

**Objective:**

To build a model that accurately classifies movie reviews based on their textual content.

**Dataset:**

This project uses the IMDB Movie Review Dataset (or specify the dataset you use). You can obtain this dataset from various sources (e.g., TensorFlow Datasets, Kaggle). If using a different dataset, please update this README accordingly.


**Dataset**

IMDB Dataset from Kaggle


**Implementation:**

The `sentiment_analysis.py` script performs the following steps:

1.  **Data Loading:** Loads the movie review dataset using pandas.
2.  **Data Preprocessing:**
    *   Converts text to lowercase.
    *   Removes punctuation and special characters.
    *   (Optional) Removes stop words.
    *   (Optional) Performs stemming or lemmatization.
3.  **Feature Extraction:**
    *   Uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert text to numerical vectors. (Other methods like Bag of Words or Word Embeddings can be used.)
4.  **Data Splitting:** Splits the data into training and testing sets.
5.  **Model Training:** Trains a Logistic Regression model (or other chosen model) on the training data.
6.  **Model Evaluation:** Evaluates the model's performance on the test data using metrics like accuracy, precision, recall, and F1-score.
7.  **(Optional) Example Predictions:** Shows a few examples of correctly and incorrectly classified reviews.


**Evaluation Metrics:**

The model's performance is evaluated using the following metrics:

*   **Accuracy:** The overall percentage of correctly classified reviews.
*   **Precision:** The proportion of correctly predicted positive reviews out of all reviews predicted as positive.
*   **Recall:** The proportion of correctly predicted positive reviews out of all actual positive reviews.
*   **F1-score:** The harmonic mean of precision and recall.
