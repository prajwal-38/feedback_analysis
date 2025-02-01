# Feedback Analysis Project

This project analyzes customer feedback (reviews) to classify whether the feedback is **positive (Good Feedback)** or **negative (Bad Feedback)** using machine learning. A **Random Forest Classifier** model is trained to predict whether feedback is good or bad, based on text reviews.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Model Training](#model-training)
- [File Structure](#file-structure)
- [License](#license)

## Project Overview

This project classifies customer feedback into two categories: **Good Feedback** and **Bad Feedback**. It uses **Natural Language Processing (NLP)** techniques to preprocess the reviews, followed by training a **Random Forest Classifier** for sentiment prediction. The model is saved as a `.pkl` file, which can be used for prediction on new reviews.

### Key Features:
- **Data Preprocessing**: Removes non-alphabetic characters, converts text to lowercase, and splits reviews into tokens.
- **Vectorization**: Converts the review text into feature vectors using `CountVectorizer`.
- **Model**: Trains a **Random Forest Classifier** to classify the reviews as good or bad.
- **Evaluation**: Evaluates the model’s accuracy and provides predictions for new reviews.

## Technologies Used

- **Python** (3.x)
- **Jupyter Notebook**: For running the analysis and model training
- **Scikit-learn**: For machine learning tasks
- **Pandas**: For data manipulation and loading the dataset
- **NumPy**: For numerical operations
- **NLTK**: For natural language processing (tokenization, stemming, etc.)
