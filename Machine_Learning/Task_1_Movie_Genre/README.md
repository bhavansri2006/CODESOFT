# Task 1: Movie Genre Classification

Objective
Build a machine learning model to predict the genre of a movie based on its plot description using Natural Language Processing (NLP) techniques.

Description
This project focuses on classifying movies into multiple genres using textual plot summaries.  
The text data is converted into numerical features using **TF-IDF Vectorization**, and a machine learning classifier is trained to predict the correct genre.

Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Natural Language Processing (NLP)

Dataset
- `train_data.txt`
- `test_data.txt`
- `description.txt`

The dataset contains movie plot descriptions along with their corresponding genres.

 Model Used
- TF-IDF Vectorizer  
- Logistic Regression / Naive Bayes (based on implementation)

Evaluation
- Accuracy: **~58%**
- Classification report includes precision, recall, and F1-score for each genre.

 Outcome
The model successfully learns patterns from textual movie descriptions and predicts movie genres with reasonable accuracy, demonstrating the application of NLP in text classification problems.

 Status
  **Completed**
