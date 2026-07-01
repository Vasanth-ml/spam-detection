# Spam Detection

## Problem Statement
Classify SMS messages as spam or legitimate (ham)
using Natural Language Processing and 
Machine Learning.

## Dataset
- Source: Kaggle - SMS Spam Collection Dataset
- Size: 5572 messages
- Target: label (ham = legitimate, spam = spam)

## Algorithm Used
Multinomial Naive Bayes

## Results
- Accuracy: 98%
- False Positive: 5 (legitimate messages marked as spam)
- False Negative: 17 (spam messages that slipped through)

## Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Re (Regular Expressions)

## Steps Performed
1. Data Loading and Exploration
2. Text Cleaning (lowercase, remove punctuation, numbers)
3. Stopwords Removal (NLTK)
4. CountVectorizer (text to numbers)
5. Train Test Split (80/20)
6. Model Training (Multinomial Naive Bayes)
7. Model Evaluation (Accuracy, Confusion Matrix)
8. Visualization (Confusion Matrix Heatmap)

## Key Findings
- Naive Bayes achieved 98% accuracy on spam detection
- Words like "free", "win", "prize" strongly indicate spam
- Text preprocessing significantly improved model performance
- CountVectorizer converted 5572 messages into 7400 unique word features

## NLP Techniques Used
- Text normalization (lowercase)
- Punctuation and number removal (regex)
- Stopwords removal (NLTK)
- Bag of Words (CountVectorizer)
