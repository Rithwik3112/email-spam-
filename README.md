# email-spam-
## 📋 Overview

This project implements a Spam Email Detection System using Naive Bayes Classifier. The system is designed to classify emails as either Spam or Ham (Not Spam) based on their content. It includes data preprocessing, visualization, model training, evaluation, and real-time spam detection.

## 🚀 Features
Data Preprocessing and Cleaning
Spam vs Ham Distribution Visualization
Word Cloud of Most Frequent Spam Words
Model Training using Multinomial Naive Bayes
Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC
Real-time Spam Detection for Custom Email Input

## 📊 Dataset
The dataset used is a collection of labeled messages with the following columns:
v1: Label (ham/spam)
v2: Message text
Sample Data:
v1,v2
ham,"Go until jurong point, crazy.."
spam,"Free entry in 2 a wkly comp to win FA Cup"

## 🛠️ Installation
Clone the repository:
git clone https://github.com/your-username/spam-email-detection.git
cd spam-email-detection
Install dependencies:
pip install -r requirements.txt
Run the code:
python spam_detection.py

## 🧪 Libraries Used
NumPy
Pandas
Matplotlib & Seaborn (for data visualization)
Scikit-learn (for machine learning models and evaluation)
WordCloud (for visual representation of spam words)

## ⚡ Usage Example
# Example Usage of Spam Detection
sample_email = 'Free Tickets for IPL'
result = detect_spam(sample_email)
print(result)
output: This is a Spam Email!


## 📈 Model Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
The model also displays:
Confusion Matrix (for both training and testing data)
ROC Curve to visualize model performance

## 📊 Visualization
Pie Chart for Spam vs Ham Distribution
Word Cloud for Most Used Words in Spam Messages

## 🙌 Acknowledgments
Dataset sourced from public repositories.
Inspired by real-world email spam filtering systems.
