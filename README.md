# Sentiment Analysis in Python

This project demonstrates sentiment analysis in Python using two different techniques:

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner) - Bag of words approach**
2. **Roberta Pretrained Model from Huggingface Pipeline**

## Tutorial

This notebook is part of a tutorial available on [YouTube](tutorial_link_here). Check it out for a detailed walkthrough.

## Steps Covered in the Notebook:

### Step 0: Read in Data and NLTK Basics
- Reading data using pandas
- Basic NLTK operations like tokenization and part-of-speech tagging

### Step 1: VADER Sentiment Scoring
- Using NLTK's SentimentIntensityAnalyzer to get sentiment scores
- Applying VADER on the entire dataset
- Visualizing VADER results

### Step 2: Roberta Pretrained Model
- Utilizing a pretrained model from Huggingface Transformers
- Comparing scores between VADER and Roberta model
- Visualizing scores between models

### Step 3: Combine and Compare
- Pairplot to compare VADER and Roberta scores

### Step 4: Review Examples
- Exploring examples where model scoring and review score differ
- Showing examples of positive 1-star and negative 5-star reviews

### Extra: The Transformers Pipeline
- Demonstrating the Transformers Pipeline for quick sentiment predictions

## How to Run
1. Ensure all dependencies are installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `transformers`)
2. Download or clone the notebook and associated dataset
3. Run each cell in the notebook sequentially

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- transformers

## Note
Make sure to replace `tutorial_link_here` in the README with the actual link to the tutorial.

