# Telegram Channel Post Classification using SVM

## Overview
This project involves classifying posts from various Telegram channels into categories such as news, sports, and entertainment using a Support Vector Machine (SVM) algorithm. The data is collected from specific Telegram channels, preprocessed, and then used to train an SVM model for classification.

## Steps

### 1. Obtain API Credentials
- Visit [my.telegram.org](https://my.telegram.org/apps) and obtain your `api_hash` and `api_id` for your mobile number on Telegram.
- Follow the documentation and process to receive and report these credentials.

### 2. Join Telegram Channels
- Join the following Telegram channels for the exercise:
  - @Tasnimnews
  - @varzesh3
  - @Film_news

### 3. Collect Initial Data
- Collect the first 20 posts from each channel and save them in a single file.
- Send this file to the Elasticsearch database.

### 4. Fetch Latest Posts
- Fetch the last 50 posts from each channel and send them to the database as well.

### 5. Categorize Content
- Categorize the collected content into political, sports, and entertainment categories.
- Only gather text content.

### 6. Initial Text Processing
- Perform initial text processing on the gathered data (e.g., cleaning the text, removing stop words, etc.).

### 7. Store Processed Data
- Save the processed data into a new file, taking note of which channel each post came from (e.g., 2 for sports news and 4 for entertainment).

### 8. Train SVM Model
- Using a simple machine learning model, gather news posts and categorize them.
- Train the SVM model with the collected data.

### 9. Evaluate Model Performance
- Evaluate the performance of the trained model.
- Consider using logistic regression for a more detailed algorithm description.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, Elasticsearch, NLP, hazm

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Run the provided Python scripts to:
   - Collect and preprocess data.
   - Train the SVM model.
   - Evaluate the model's performance.

## Results
- Classification accuracy of the SVM model.
- Comparison of model performance with other algorithms (e.g., logistic regression).

## Conclusion
This project demonstrates the classification of Telegram channel posts using SVM, providing insights into content categorization and the effectiveness of machine learning models for text classification.

]
