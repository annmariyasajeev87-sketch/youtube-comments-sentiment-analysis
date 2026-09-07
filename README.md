# NLP-Based Sentiment Analysis of YouTube Comments Using Machine Learning

## 1. Project Title

**NLP-Based Sentiment Analysis of YouTube Comments Using Machine Learning**

## 2. Project Description

This project develops a sentiment analysis system for YouTube comments using Natural Language Processing (NLP) and Machine Learning. The system processes comments and classifies them into **Positive, Neutral, or Negative** sentiments.

## 3. Objectives

* To preprocess and clean YouTube comments.
* To apply NLP techniques to textual data.
* To convert text into numerical features using TF-IDF.
* To train a machine learning model for sentiment classification.
* To classify comments into Positive, Neutral, and Negative sentiments.
* To evaluate the performance of the model.

## 4. Technologies Used

* **Python** – Programming language
* **Google Colab** – Development platform
* **Pandas** – Data processing
* **NumPy** – Numerical operations
* **NLTK** – NLP preprocessing
* **Scikit-learn** – TF-IDF, Logistic Regression, and evaluation
* **Matplotlib & Seaborn** – Data visualization

## 5. NLP Techniques

The project uses the following NLP techniques:

* Lowercase conversion
* URL removal
* HTML tag removal
* Special character and number removal
* Tokenization
* Stopword removal
* Lemmatization
* TF-IDF feature extraction

These techniques help clean and prepare the comments for machine learning.

## 6. Machine Learning Model

**Logistic Regression** is used as the classification algorithm. It learns patterns from TF-IDF features and predicts whether a comment is **Positive, Neutral, or Negative**.

## 7. Dataset Details

* **Dataset Name:** YouTube Comments Sentiment Dataset
* **Dataset File:** `YoutubeCommentsDataSet.csv`
* **Source:** Kaggle
* **Initial Dataset Size:** 18,408 rows × 2 columns
* **Final Dataset Size:** 18,139 rows × 3 columns
* **Sentiment Classes:** Positive, Neutral, Negative

## 8. Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Text Preprocessing
   ↓
Train-Test Split
   ↓
TF-IDF Feature Extraction
   ↓
Logistic Regression
   ↓
Sentiment Prediction
   ↓
Model Evaluation
```

## 9. Train-Test Split

The dataset is divided into **80% training data** and **20% testing data**. Stratification is used to maintain the sentiment distribution in both datasets.

## 10. Results/Evaluation

The model is evaluated using Accuracy, Precision, Recall, F1-Score, Classification Report, and Confusion Matrix.

The results show that the Logistic Regression model provides reasonable performance for YouTube comment sentiment classification.

 ## 11. Limitations

* Difficulty in understanding sarcasm.
* Slang and informal language may affect predictions.
* Mixed-language comments may be difficult to classify.
* Emojis and special expressions may lose information during preprocessing.
* Ambiguous comments may be incorrectly classified.

## 12. Future Scope

The project can be improved by:

* Using a larger and more diverse dataset.
* Supporting multiple languages.
* Improving handling of slang and emojis.
* Using advanced NLP and deep learning models.
* Developing a real-time sentiment analysis system.
* Developing a web application for sentiment prediction.

## 13. Conclusion

This project demonstrates the use of NLP and Machine Learning for automatic sentiment analysis of YouTube comments. TF-IDF is used for feature extraction, while Logistic Regression is used to classify comments into Positive, Neutral, and Negative sentiments.

## 14. Google Colab Link

[Open Google Colab Project]https://colab.research.google.com/drive/14IkvgZyabYTkATKTE4LHrb6HrqPV6gIM?usp=sharing 
