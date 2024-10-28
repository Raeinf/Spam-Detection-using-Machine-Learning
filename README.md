# Spam-Detection-using-Machine-Learning

This project contains a Jupyter notebook that builds a spam detection system using various machine learning models. The notebook guides users through data preprocessing, model training, and performance evaluation to classify messages as spam or not spam.

## Project Overview

Spam detection is a common text classification problem that involves identifying unsolicited or irrelevant messages. In this project, we apply several machine learning algorithms to classify messages, evaluate each model’s performance, and compare results based on multiple metrics.

### Models Used

The following machine learning models are implemented and compared in this project:
- **Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**

### Evaluation and Comparison

The models are evaluated based on the following metrics:
- **Accuracy**: Measures the overall correctness of predictions.
- **Precision**: Indicates how many of the predicted spam messages are actually spam.
- **Recall**: Reflects how well the model identifies all spam messages.
- **F1-score**: Provides a harmonic mean of precision and recall, balancing both aspects.

These metrics help us assess each model's effectiveness, enabling a comprehensive comparison of their performance.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, nltk

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/spam-detection-ml.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook main.ipynb
    ```
2. Run the cells step-by-step to preprocess data, train each model, and evaluate performance.

### Results

Each model's results are documented in terms of accuracy, precision, recall, and F1-score, providing insight into their strengths and weaknesses for spam detection.


