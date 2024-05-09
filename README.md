# Sarcasm Detection in News Headlines

This project focuses on developing a machine learning model to classify news headlines as sarcastic or non-sarcastic using natural language processing (NLP) techniques. The dataset comprises headlines sourced from reputable news outlets (TheOnion and HuffPost) totaling 28,619 instances. The goal is to build a robust model capable of accurately discerning sarcasm in headlines, aiding in automatic categorization and analysis of news content.

## Project Overview

- **Data Exploration**: Understand features, address missing values, duplicates, and analyze data distributions.
- **Preprocessing**: Standardize text, remove noise (HTML tags, URLs, punctuation, numbers, stopwords), and perform lemmatization. Engineer features like headline length and tokenization.
- **Model Selection**: Utilize LSTM variants with embedding techniques (Word2Vec and GloVe) to enrich data representation.
- **Model Training**: Train and tune models using hyperparameters to achieve optimal performance.
- **Evaluation**: Assess model accuracy using training and validation metrics.

## Objectives

- Develop a sarcasm detection system for news headlines.
- Improve precision and consistency of sarcasm detection using expertly crafted news headlines.
- Contribute to sentiment analysis and language understanding in computational linguistics.

## Methodology

1. **Data Collection and Preprocessing**:
   - Convert text to lowercase, strip HTML tags, remove URLs, punctuation marks, numbers, and stopwords.
   - Lemmatize text to ensure data quality.

2. **Model Selection and Comparison**:
   - Implement LSTM models with pre-trained Word2Vec and GloVe embeddings.
   - Evaluate model performance using standard metrics.

3. **Training and Evaluation**:
   - Train selected models on preprocessed data.
   - Evaluate models using accuracy metrics (training accuracy, validation accuracy).

4. **Analysis and Interpretation**:
   - Analyze results to understand model strengths and weaknesses.
   - Identify factors impacting sarcasm detection accuracy.

## Dataset Access

The dataset contains 28,619 news headlines labeled as sarcastic or non-sarcastic and is available for unrestricted access:

- [Sciencedirect Article](link_to_article)
- [GitHub Repository](link_to_repository)

## Contributors

- [Srikar Rambhatla](https://github.com/SrikarRambhatla)
- [Visesh Paka](https://github.com/visheshpaka)

## Acknowledgments

Special thanks to TheOnion and HuffPost for providing the dataset and enabling research in sarcasm detection.

