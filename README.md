Project Overview
This project analyzes customer sentiments from airline-related tweets to classify them as positive, negative, or neutral. Using Natural Language Processing (NLP) and machine learning models (Logistic Regression, Random Forest, and Naive Bayes), the goal is to understand how passengers feel about different airlines.

Tech Stack
Python (pandas, numpy, scikit-learn, nltk)
Machine Learning Models: Logistic Regression, Random Forest, Naive Bayes
Vectorization: TF-IDF
Deployment Ready: Saved model using Pickle
Project Structure
augest_project/
│── notebooks/              # Jupyter notebooks (data cleaning, modeling, evaluation)  
│── models/                 # Saved pickle files (.pkl) for model & vectorizer  
│── data/                   # Dataset (raw + cleaned)  
│── .gitignore              # Ignored files (checkpoints, cache, etc.)  
│── README.md               # Project documentation  

How to RUN
git clone https://github.com/yourusername/augest_project.git
cd augest_project
Install depedencies
pip install -r requirements.txt
Open the notebook and run all cells.
Test predictions with the trained model (saved as .pkl).
Results
Logistic Regression performed the best with ~80% accuracy.
Negative sentiments were predicted with the highest precision.
The model can be extended for real-time sentiment monitoring
Future Improvements
Build a Streamlit web app for live predictions.
Expand dataset to include more airlines.
Try deep learning models (LSTMs, Transformers).

# ✈️ Airline Tweet Sentiment Analysis  

This project analyzes airline-related tweets to classify sentiments as **Positive, Neutral, or Negative**.  
It includes **data preprocessing, model training (Logistic Regression, Random Forest, Naive Bayes)**, and saving the best model for deployment.  

📂 Tools used: Python, Scikit-learn, NLTK, TF-IDF  
🎯 Goal: Understand customer sentiment and provide insights for airlines.  

👩‍💻 Author: Rutuja Anil Pawar  






