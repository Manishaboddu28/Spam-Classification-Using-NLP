# 📧 Spam Classification using Natural Language Processing (NLP)
This project demonstrates how to build a spam message classifier using Natural Language Processing (NLP) techniques and a Logistic Regression model. It’s a beginner-friendly, end-to-end implementation of text classification using real-world SMS data.

## 🚀 Project Overview
 - Spam messages can clutter inboxes and pose security threats. This project uses Python and the scikit-learn library to classify SMS messages as either spam or ham (not spam) using the following steps:

- Loading and preprocessing a real-world SMS dataset.

- Converting text into numerical format using CountVectorizer.

- Training a Logistic Regression model on the vectorized data.

- Evaluating performance using accuracy, confusion matrix, and classification report.

## 🛠️ Technologies & Libraries Used
Python 3

Pandas – Data manipulation

Scikit-learn – ML models and evaluation

CountVectorizer

LogisticRegression

Train-Test Split

Accuracy Score, Confusion Matrix, Classification Report

## 📂 Dataset Info
The dataset includes thousands of labeled SMS messages. Each entry contains:

- v2: Message text

- Label: Either "ham" or "spam"

(Note: The dataset is loaded locally in the notebook; make sure to update the path based on your project folder.)

## 📊 Model Performance
After training the model:

- High accuracy on both training and testing data

- Confusion Matrix and Classification Report help analyze performance in detail

## 🧠 Key Learning Outcomes
- Basics of Natural Language Processing (NLP)

- Converting raw text into machine-readable format

- Training and evaluating a binary classifier

- Understanding precision, recall, and F1-score

## 📌 How to Run
 - Clone the repository or download the .ipynb file.

- Make sure you have the required libraries installed:

> pip install pandas scikit-learn

- Update the dataset path in the notebook.

- Run the notebook cell-by-cell in Jupyter Notebook, VS Code, or Google Colab.
