  #Title: Exploratory Data Analysis & Preprocessing in NLP

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA) and Text Preprocessing in Natural Language Processing (NLP)**.

The main objective is to explore a publicly available textual dataset, identify patterns and data-quality issues, and preprocess the text for future NLP and machine learning applications.

##  Objectives

* Understand and explore the textual dataset
* Analyze data distribution
* Identify missing and duplicate data
* Analyze text length and word frequency
* Perform unigram, bigram, and trigram analysis
* Analyze sentiment distribution
* Clean and normalize text data
* Perform tokenization
* Remove stop words
* Apply lemmatization
* Visualize important patterns and insights

## 📊 Dataset

**Dataset:** IMDb Movie Reviews Dataset

The IMDb Movie Reviews dataset contains movie reviews with sentiment labels. It is widely used for NLP and sentiment-analysis tasks.

**Dataset Source:** Publicly available IMDb movie review dataset.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* Jupyter Notebook

## 🔍 Exploratory Data Analysis

The following analyses are performed:

1. Dataset shape and structure
2. Missing-value analysis
3. Duplicate-value analysis
4. Sentiment distribution
5. Review-length analysis
6. Word-frequency analysis
7. Unigram analysis
8. Bigram analysis
9. Trigram analysis
10. Identification of noisy data
11. Data visualization

##  Text Preprocessing

The text preprocessing pipeline includes:

* Lowercasing
* HTML tag removal
* URL removal
* Special-character removal
* Punctuation removal
* Extra-space removal
* Tokenization
* Stop-word removal
* Lemmatization

## Visualizations

The project contains visualizations for:

* Sentiment distribution
* Review-length distribution
* Most frequent words
* Unigrams
* Bigrams
* Trigrams
* Word cloud

##  Key Insights

EDA helps identify:

* Distribution of positive and negative reviews
* Most frequently used words
* Common word combinations
* Variation in review lengths
* Missing and duplicate records
* Noisy and unstructured text

These insights help determine suitable preprocessing and feature-engineering techniques for future NLP models.

##  Future Scope

The processed dataset can be used for:

* Sentiment classification
* Text classification
* TF-IDF feature extraction
* Machine learning models
* Word embeddings
* LSTM/GRU models
* Transformer-based models such as BERT

##  Repository Structure

```text
Week-1-NLP-EDA-Preprocessing/
│
├── README.md
├── notebooks/
│   └── NLP_EDA_Preprocessing.ipynb
│
├── src/
│   └── preprocessing.py
│
├── outputs/
│   ├── sentiment_distribution.png
│   ├── text_length_distribution.png
│   ├── word_frequency.png
│   └── ngram_analysis.png
│
├── dataset/
│   └── README.md
│
├── report/
│   └── Week_1_NLP_Report.docx
│
├── requirements.txt
└── .gitignore
```

## Author

**Arfat Sherkhan**

AIML Engineering Student

## 📌 Task

**Week 1: Exploratory Data Analysis & Preprocessing in NLP**

This project was completed as part of the Week 1 NLP task.
