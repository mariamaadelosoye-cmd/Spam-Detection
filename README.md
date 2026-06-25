# Email Spam Detection using Natural Language Processing

## Overview

This project builds a machine learning model capable of classifying Emails as either **Spam** or **Ham (Legitimate Messages)** using Natural Language Processing (NLP) techniques.

The project demonstrates the complete NLP workflow, including data exploration, text preprocessing, feature extraction, model training, evaluation, and deployment-ready model persistence.

---

## Problem Statement

Spam messages are a common issue in digital communication. The objective of this project is to automatically identify whether an Emails is spam or legitimate based on its textual content.

This is a binary text classification problem and a classic application of Natural Language Processing.

---

## Dataset

The dataset consists of Emails labeled as:

* **0 (Ham)** – Legitimate messages
* **1 (Spam)** – Unwanted promotional or fraudulent messages

Each record contains:

* Message text
* Corresponding label

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Examined dataset structure
* Checked class distribution
* Analyzed message length patterns

### 2. Text Preprocessing

A custom preprocessing function was created to:

* Remove punctuation
* Tokenize text
* Remove stopwords

This reduces noise and improves the quality of the features used for training.

### 3. Feature Extraction

The text data was transformed into numerical features using:

* Bag of Words (CountVectorizer)
* TF-IDF (Term Frequency–Inverse Document Frequency)

### 4. Model Training

A machine learning pipeline was built using Scikit-learn to combine preprocessing, feature extraction, and classification into a single workflow.

### 5. Model Evaluation

The model was evaluated using:

* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics were selected because spam detection datasets are often imbalanced, making accuracy alone insufficient.
---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn


---

## Key Skills Demonstrated

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Engineering
* Machine Learning
* Classification
* Model Evaluation
* Scikit-learn Pipelines
---

## Future Improvements

* Hyperparameter tuning
* N-gram feature engineering
* Deployment using Streamlit
* Real-time SMS classification interface

---

## Author

Mariam

Machine Learning and Data Science Portfolio Project
