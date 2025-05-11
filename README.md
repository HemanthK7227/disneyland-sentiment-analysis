# Sentiment Analysis of Disneyland California Reviews Using Text Mining

## Overview
This project leverages text mining and machine learning techniques to analyze Disneyland California guest reviews. Using the Kaggle dataset, we applied sentiment analysis to categorize reviews into positive, neutral, and negative sentiments, enabling actionable insights into customer experiences. This analysis helps businesses gauge customer satisfaction, track the impact of marketing campaigns, and identify areas for improvement.

## Objective
The primary objective is to build a sentiment analysis model using k-NN and Naive Bayes algorithms to process and classify guest reviews from Disneyland California. The project also aims to extract insights from customer opinions, enabling marketing teams to tailor strategies to customer needs.

## Technologies Used
- **RapidMiner** for sentiment analysis and text mining.
- **Python** and **R** for data preprocessing, tokenization, and model evaluation.
- **k-NN Algorithm** for sentiment classification.
- **Naive Bayes** for improving sentiment prediction accuracy.
- **Text Mining** techniques, including stopword removal, stemming, and feature extraction.

## Data
The dataset was sourced from Kaggle and contains over 42,000 reviews from three Disneyland branches (California, Paris, Hong Kong). For this project, a subset of 3,000 reviews from Disneyland California was analyzed, with 1,000 reviews for each sentiment label: positive, neutral, and negative.

## Model Process
1. **Data Preprocessing:** The reviews were tokenized, stopwords removed, and text data transformed using TF-IDF.
2. **Model Construction:** Two classification models were tested using k-NN and Naive Bayes to predict the sentiment of each review.
3. **Cross Validation:** The data was split into 10-folds for cross-validation to prevent overfitting.
4. **Evaluation:** The models were evaluated based on their accuracy in predicting positive, negative, and neutral sentiments.

## Results
- **Initial Model Accuracy:** 52.1% (with k-NN)
- **Improved Model Accuracy:** 59.27% (with Naive Bayes)
- The improved model showed better performance in predicting positive and negative sentiments compared to neutral sentiments.

## Recommendations
- Implement **ensemble modeling** to improve accuracy.
- **Feature engineering** can be further explored to enhance model predictions.
- Fine-tune **neutral sentiment prediction** to increase overall accuracy.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/HemanthK7227/disneyland-sentiment-analysis.git
