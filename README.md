# SENTIMENT-ANALYSIS-FOR-MOVIE-REVIEW-USING-NAIVE-BAYES
Cs585  Natural Language Processing - Final Project

### Overview

This project implements a Naïve Bayes classifier from scratch to perform sentiment analysis on movie reviews. The classifier is trained and tested using a publicly available dataset, allowing us to categorize reviews as positive or negative. 

### Objectives

- Develop and evaluate a Naïve Bayes classifier without relying on pre-built Python packages.
- Perform exploratory data analysis and preprocessing on a chosen dataset.
- Implement text preprocessing techniques and apply a binary Bag of Words model with "add-1" smoothing.
- Train and test the classifier, calculate various performance metrics, and evaluate its effectiveness.

### Features

- **Custom Naïve Bayes Classifier**: Built from the ground up without external machine learning libraries.
- **Dynamic Training Size**: Accepts user-defined training set size (between 20% to 80%) via command line.
- **Text Preprocessing**: Handles raw input text, applies necessary cleaning, and converts it into a binary Bag of Words format.
- **Performance Evaluation**: Computes key metrics such as accuracy, precision, recall, specificity, F-score, etc.
- **Interactive User Input**: Classifies new sentences entered by the user in real time.

### How to Run

1. **Command Line Execution**:
   Run the script with:
   ```bash
   python CS585_P02_AXXXXXXXX.py TRAIN_SIZE
   ```
   - Replace `AXXXXXXXX` with your IIT A number.
   - `TRAIN_SIZE` is a number between 20 and 80 representing the percentage of the dataset to use for training.

2. **Example Command**:
   ```bash
   python CS585_P02_A11111111.py 60
   ```

### Deliverables

- **Python Code File(s)**: Main file and any supporting files with appropriate naming conventions.
- **Presentation Slides**: Summary of the project's methodology, results, and conclusions in PPTX or PDF format.
- **Project Report**: Detailed observations, conclusions, and performance analysis in PDF format.

### Results

- The classifier's performance was evaluated using different training set sizes (70% and 80%), showing slight variations in accuracy, recall, and precision. 
- Generally, the classifier performed slightly better with a 70% training set, demonstrating its robustness across different data sizes.

### Observations and Conclusions

- The algorithm consistently performs well across various training sizes, showing reliable results in both precision and accuracy.
- It exhibits marginally better performance with 70% of the data used for training, indicating an optimal balance between training size and accuracy.
