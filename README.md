# Fake-News-Detectionc 
Key Aspects:
Problem Statement:
Widespread misinformation circulating online poses a threat to modern societies.
Our goal was to create an automated system capable of detecting fake news articles.
Data Collection and Preprocessing:
Collected a labeled dataset containing both real and fake news articles.
Applied text preprocessing techniques (tokenization, stop-word removal, stemming) to clean the data.
Feature Extraction:
Used TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text data into numerical features.
Represented each article as a vector of TF-IDF scores.
Logistic Regression Model:
Trained the model on preprocessed data using the TF-IDF vectors as input features.
Logistic regression is suitable for binary classification and predicts probabilities.
Model Evaluation:
Split the dataset into training and testing subsets.
Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.
Results:
Achieved an accuracy of approximately 92% in distinguishing real from fake news articles.
Integration into news platforms can help flag potentially misleading content.
