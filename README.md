# Kaggle_Disaster_Tweets_NLP
A machine learning project for the Kaggle competition "Natural Language Processing with Disaster Tweets," using a TF-IDF vectorizer and a Logistic Regression classifier with hyperparameter tuning.

📌 Project Overview

Goal: Build a machine learning model that predicts which tweets are about real disasters.

Dataset: Provided by Kaggle (tweets + labels).

Approach:

Text preprocessing (cleaning, tokenization, stopword removal).

Feature extraction using TF-IDF.

Model training with Logistic Regression (baseline).

Evaluation using Accuracy and F1 Score.

🛠️ Tech Stack

- Python 🐍

- Pandas, NumPy

- Scikit-learn

- NLTK / re (text preprocessing)

- Matplotlib / Seaborn (visualization)

📂 Repository Structure
📁 CalmMateAI/
 ├── Natural_Language_Processing_with_Disaster_Tweets_2.ipynb   # Main notebook
 ├── README.md                                                   # Project description
 └── submission.csv                                              # Kaggle submission file (output)

🚀 How to Run

Clone this repository:

git clone https://github.com/saberabanu0001/CalmMateAI.git
cd CalmMateAI


Open the notebook in Jupyter or Google Colab.

Install required libraries:

pip install -r requirements.txt


Run all cells in Natural_Language_Processing_with_Disaster_Tweets_2.ipynb.

📊 Results

Baseline Model: Logistic Regression with TF-IDF features.

Achieved around X% accuracy on validation set (update with your result).

📌 Future Improvements

Try advanced models (Naive Bayes, Random Forest, XGBoost).

Use deep learning (LSTM, BERT).

Perform hyperparameter tuning for better performance.

📜 License

This project is for learning purposes. Free to use and modify.
