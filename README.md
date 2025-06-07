# satish05112003-sentiment_analysis_using_ML
Developed a logistic regression model using the Sentiment140 dataset (1.6M tweets) to classify tweet sentiments. Implemented text preprocessing with NLTK, feature extraction using TF-IDF, and achieved ~83% accuracy. Tools: Python, Colab, Scikit-learn, NLTK.


Sentiment Analysis on Tweets Using ML (Sentiment140)
This machine learning project analyzes public sentiment from tweets using the Sentiment140 dataset, which contains 1.6 million tweets labeled as positive or negative.

🧠 Objective:
To build a binary classification model that predicts sentiment (positive/negative) based on the text of a tweet.

⚙️ Technologies Used:
Python

Google Colab

NLTK for preprocessing

Scikit-learn for vectorization and modeling

Kaggle API for downloading the dataset

🧹 Data Preprocessing:
Removed user handles, special characters, URLs, and digits

Tokenized tweets

Removed stopwords using nltk.corpus.stopwords

Applied stemming using PorterStemmer

📊 Feature Extraction:
Converted cleaned tweets into numerical form using TF-IDF Vectorizer

🧪 Model Training:
Model Used: Logistic Regression

Train-Test Split: 80-20

Evaluation Metric: Accuracy Score

✅ Results:
Achieved ~83% accuracy on the test data

Robust model capable of analyzing large-scale tweet sentiment

🔗 Project Notebook:
👉 https://colab.research.google.com/drive/1lSHp_23n_Yu7svgMwj75TRTeE_RZpSBo?usp=sharing
