# Personality-Detection-NLP
This project implements a personality prediction pipeline using text data from a Kaggle dataset. The goal is to classify individuals into one of 16 personality types based on their posts. The pipeline involves text preprocessing, feature extraction, handling class imbalance, and training machine learning models. Key steps include:

    Data Exploration:
        Loading the dataset and examining the distribution of personality types.
        Mapping personality types to numeric labels for modeling.

    Text Preprocessing:
        Cleaning text by removing non-alphabetic characters and extra whitespace.
        Lemmatization to normalize words to their base forms.
        Removing stopwords to retain meaningful information.

    Feature Engineering:
        Generating features using CountVectorizer and TF-IDF Vectorizer for text representation.
        Combining vectorized features into a sparse matrix for model input.

    Handling Class Imbalance:
        Applying SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.

    Model Training and Evaluation:
        Training a Bernoulli Naive Bayes classifier and a Random Forest classifier.
        Comparing model performance using accuracy scores.

This project demonstrates a comprehensive approach to text-based personality classification, leveraging natural language processing (NLP) and machine learning techniques.

