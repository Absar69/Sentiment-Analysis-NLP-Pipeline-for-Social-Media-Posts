# **Urdu Sentiment Analysis NLP Pipeline**

A comprehensive Natural Language Processing (NLP) pipeline to classify sentiments (positive, negative, neutral) in Urdu social media posts. This project leverages the [Urdu Sarcastic Tweets Dataset](https://www.kaggle.com/datasets/shumailakhan/urdu-sarcastic-tweets-dataset) and tackles the unique challenges of Urdu language processing and noisy social media data.

---

## **Project Overview**

This pipeline is designed to:
- Analyze Urdu social media posts.
- Handle linguistic complexities like morphology, grammar, and script.
- Provide sentiment classification for customer feedback, audience engagement, and public opinion analysis.

---

## **Features**

### 1. **Text Preprocessing**
- Custom removal of Urdu stopwords.
- Handling of punctuation, emojis, hashtags, URLs, and spelling variations.
- Filtering short and incomplete posts.

### 2. **Stemming and Lemmatization**
- Reduction of gender and plurality-based word inflections.
- Lemmatization to restore words to their root forms.

### 3. **Feature Extraction**
- Tokenization optimized for Urdu's right-to-left script.
- TF-IDF vectorization for term importance.
- Word2Vec embeddings for contextual relationships.

### 4. **N-gram Analysis**
- Unigram, bigram, and trigram extraction with frequency analysis.

### 5. **Sentiment Classification**
- Machine learning models: Logistic Regression, SVM, Naive Bayes.
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score.

---

## **Dataset**

The project uses the [Urdu Sarcastic Tweets Dataset](https://www.kaggle.com/datasets/shumailakhan/urdu-sarcastic-tweets-dataset), which contains labeled Urdu tweets for sentiment analysis. Download the dataset and place it in the `data/` directory.
