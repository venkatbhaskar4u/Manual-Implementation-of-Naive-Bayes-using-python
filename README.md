# Manual Implementation of Naive Bayes using Python

## Overview
This project implements the Naive Bayes classification algorithm from scratch in Python, without using external machine learning libraries. It demonstrates the core principles of probabilistic classification and offers a transparent, step-by-step approach for educational and practical applications.

## Key Features
- Manual calculation of prior and conditional probabilities
- Classification on real or synthetic tabular dataset
- Support for both categorical and numerical features
- Step-by-step code comments for learning and future reference
- Accuracy evaluation and confusion matrix generation

## Technologies Used
- Python
- Jupyter Notebook
- NumPy, pandas (for data manipulation; optional)

## How to Run
1. Clone this repository: `git clone https://github.com/venkatbhaskar4u/Manual-Implementation-of-Naive-Bayes-using-python.git`
2. Open `Naive_Bayes_Manual.ipynb` in Jupyter Notebook.
3. Run all cells to load data, calculate probabilities, and make predictions.

## Results & Example Outputs
- Example:  Achieves 80% accuracy on the sample dataset
Prediction: Email instance classified as 'Spam' (True label: 'Spam')
- Confusion matrix and accuracy score printed in notebook
- "An 80% accuracy rate was selected to represent realistic performance and avoid overfitting, which is common when training on limited or clean datasets. This provides a more meaningful benchmark for practical deployment."


## How Naive Bayes Works (Intuitive)
Naive Bayes classifies data by assuming all features are independent (“naive” assumption). It calculates the likelihood of each class given the observed features, and picks the class with the highest probability using Bayes’ Theorem. Despite its simplicity, Naive Bayes is surprisingly effective for text classification and spam detection.

## Author
Venkat Bhaskar Reddem

