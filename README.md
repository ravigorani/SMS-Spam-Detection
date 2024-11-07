# SMS Spam Detection Using Naive Bayes

## Project Overview
This project aims to classify SMS messages as "Spam" or "Ham" (Non-Spam) using Natural Language Processing (NLP) and machine learning. The model uses a Naive Bayes algorithm, which is widely used in text classification due to its simplicity and effectiveness with high-dimensional data like text.

## Dataset
The dataset used for this project contains labeled SMS messages. Each message is classified as either "spam" or "ham" (non-spam). 

### Dataset Structure
- `label`: Specifies whether the message is "spam" or "ham".
- `message`: The SMS text message content.

## Requirements
The following Python libraries are required to run this project:
- `numpy`
- `pandas`
- `scikit-learn`
- `nltk` (Natural Language Toolkit)

## Usage

1. **Data Preprocessing**:
   - Load the dataset and clean the text data by removing any punctuation, converting text to lowercase, and removing stop words.
   - Tokenize the text and transform it into numerical features using techniques like **TF-IDF** (Term Frequency-Inverse Document Frequency) to prepare for model training.

2. **Training the Model**:
   - Split the dataset into training and test sets.
   - Train the Naive Bayes classifier using the training data.

3. **Making Predictions**:
   - Use the trained model to predict whether new SMS messages are "spam" or "ham" based on their text content.

