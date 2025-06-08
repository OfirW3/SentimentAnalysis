# Emotion Classification Model

This project is a machine learning model that classifies sentences based on the emotion expressed — either positive or negative. It was developed as part of the Technion AI Learning Program to demonstrate a practical end-to-end machine learning pipeline using real-world text data.

## Overview

- The dataset includes:
  - Sentences labeled with positive or negative sentiment
  - Country and geographical metadata about the author of each sentence
- The model uses TF-IDF (Term Frequency–Inverse Document Frequency) to convert sentences into numerical vectors
- A K-Nearest Neighbors (KNN) classifier is trained on these vectors to recognize emotional patterns and classify new sentences
- The notebook also includes a simple linear regression demonstration predicting country population based on land area (included for general ML practice)

## Machine Learning Pipeline

1. **Data Preprocessing**
   - Cleaned sentence and country data
   - Transformed text into numeric features using TF-IDF
   - Prepared structured data for modeling

2. **Model Training and Evaluation**
   - Trained a KNN classifier for binary sentiment classification
   - Evaluated model accuracy on labeled data

3. **Bonus: Linear Regression**
   - Built a simple linear regression model to predict country population using land size
   - Used as an educational extension unrelated to sentiment classification

## Visualizations

- Word clouds showing the most frequent words in positive and negative sentences
- Bar plots for country frequency in the dataset
- Scatter plot showing population vs. land size for regression

Note: There are no visualizations connecting sentiment to country in the current version.

## Technologies Used

- Google Colab (Jupyter Notebook)
- Python libraries:
  - pandas, numpy
  - scikit-learn
  - matplotlib, seaborn, wordcloud

## How to Run

1. [Open the notebook in Google Colab](https://colab.research.google.com/drive/1THvkdhfBE2RsQnvwAHn3s1EDLcRpfdhS?usp=sharing)
2. Run all cells in order to:
   - Load and inspect the dataset
   - Train and evaluate the sentiment classifier
   - Generate visualizations
   - Run the regression example

## Acknowledgments

This project was completed as part of the Technion AI Learning Program and is intended for educational use to demonstrate core machine learning techniques using text data.
