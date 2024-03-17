# Fake News Classifier using Logistic Regression 

This project is a simple news classifier that uses logistic regression for prediction. It is built using Python's NLTK library for text preprocessing, TfidfVectorizer for feature extraction, and Streamlit for creating a web application.

## Installation

1. Make sure you have Python installed on your machine.
2. Clone the repository:

   ```bash
   git clone https://github.com/your-username/news-classifier.git
3. Navigate to the project directory:

   ```bash
   cd news-classifier

4. Install the required dependencies. Ensure you have Python installed in your Pycharm::

## Usage

 1. Run the Streamlit app using the following command:
    ```bash
    streamlit run app.py
 2. Open the provided URL in your web browser to access the Fake News Detector.
 3. Enter a news article in the input text box and press Enter.



## Components

## 1. Data Preprocessing:
    You can download the dataset used in this model fromt this link - https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification?resource=download
   1. Filling missing values in the dataset.
   2. Applying stemming to the news content.
   3. Vectorizing the text data using TF-IDF Vectorizer.
## 2. Model Training:
   A Logistic Regression model is trained on the preprocessed data to classify news articles as fake or real.

## 2. Streamlit Web Application:
   The Streamlit web application provides a user-friendly interface for users to input news articles and get predictions on their authenticity.

