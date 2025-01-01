# Aspect-Based Sentiment Analysis (ABSA) of Text from *"Mind Platter"*

This Jupyter Notebook explores Aspect-Based Sentiment Analysis (ABSA) to uncover sentiments related to specific aspects within the text. Developed as a final project for Natural Language Processing course, this project analyzes text from the book Mind Platter by Najwa Zebian, identifying sentiments associated with different life experiences.

## Project Overview
This project aims to:
* Extract aspects from text using Natural Language Processing (NLP) techniques.
* Classify sentiments for each extracted aspect as positive, negative, or neutral.
* Train a classifier to perform sentiment analysis with Multinomial Naïve Bayes (MNB).

## Key Components
* Data Loading: Loads selected chapters from Mind Platter into a structured format.
* Preprocessing: Cleans the text by removing stopwords, and punctuation, and converting it to lowercase.
* Aspect Extraction: Uses Part-of-Speech (POS) tagging and dependency parsing to identify key aspects, such as adjective-noun and verb-adverb pairs.
* Sentiment Analysis: Applies the VADER sentiment analyzer to determine sentiment polarity.
* Model Building: Trains a Multinomial Naïve Bayes classifier with aspect-sentiment pairs to perform sentiment classification on new text.

## Methodology
1. **Text Preprocessing**: Tokenization, removal of noise, and conversion to lowercase for consistent input.
2. **Aspect Extraction**: Aspect extraction is performed in two parts:
   - **Selected Chapters**: Aspects are extracted and analyzed for each selected chapter individually.
   - **All Chapters as a Whole**: Aspects are extracted across all chapters combined to provide an overall analysis of sentiment distribution.
3. **Sentiment Classification**:
   - **VADER Sentiment Analysis**: Calculates polarity for each aspect (positive, neutral, or negative).
   - **Aspect-Based Sentiment Analysis (ABSA)**: Classifies aspects within each chapter, displaying sentiment distributions.


## Results
The model achieved 84% accuracy on individual chapters and 66% accuracy when analyzing chapters as a whole.
Sentiment distribution highlights were particularly accurate for positive and neutral sentiments, with opportunities for improving negative sentiment classification.


## Results
* The model achieved 84% accuracy on individual chapters and 66% accuracy when analyzing chapters as a whole.
* Sentiment distribution highlights were particularly accurate for positive and neutral sentiments, with opportunities for improving negative sentiment classification.
  
# #Requirements
Install the necessary libraries:

    pip install nltk spacy vaderSentiment scikit-learn

More detail in report. 

## Contributors 
- Hafsa Hafeez Siddiqui 
- Aqsa Khan
