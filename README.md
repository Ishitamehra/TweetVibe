**Sentiment Analysis on Twitter Data**

**Introduction**
This project focuses on enhancing the accuracy of the Support Vector Machine (SVM) algorithm for sentiment analysis on Twitter data. By implementing various preprocessing techniques to handle noisy and multilingual data, we aim to improve the sentiment classification accuracy for tweets.

**Features**:

1- **Multilingual Support:** Converts multilingual tweets to English using the Translator API.
2- **Noise Handling:** Removes URLs, symbols, special characters, stop words, and corrects misspelled words.
3- **Feature Extraction:** Extracts and selects relevant features to improve model accuracy.
4- **Multiple Models:** Compares the performance of Bernoulli Naive Bayes, SVM, and Logistic Regression classifiers.
5- **Data Visualization:** Provides visual insights into the data through word clouds and other visualizations.
6- **Evaluation Metrics:** Uses accuracy, F1-score, and ROC-AUC score for model evaluation.

**Prerequisites**

Python 3.6 or higher
Tweepy for Twitter API
Translator API for language conversion
TextBlob for text processing
Scikit-learn for machine learning algorithms
Matplotlib and WordCloud for data visualization