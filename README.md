🐦 Twitter Sentiment Analysis Dashboard using RNN
-----------------------------------------------------
🚀 Project Overview
----------------------
This project performs real-time sentiment analysis on user-entered tweets.

Built using Python with TensorFlow/Keras.

Focus on classifying tweets as Positive or Negative using a Recurrent Neural Network (RNN) model.

User manually enters any tweet text at runtime, and the model predicts the sentiment.

🗃️ Data Source
--------------------
Source File: Twitter Sentiment Dataset (from Kaggle or similar)

Possible Data Columns:

Tweet Text

Sentiment Label (Positive / Negative)

🛠️ Technologies Used
-----------------------
Python

TensorFlow / Keras

NumPy

Pandas

Scikit-learn

NLTK / TextBlob (For Text Preprocessing)

🧱 Model Architecture
--------------------------
Recurrent Neural Network (RNN)

Layers Used:

Embedding Layer

RNN / LSTM / GRU Layer

Dense Layer

Output Layer (Sigmoid Activation)

📏 Key Steps in the Project
-----------------------------------
User enters tweet text at runtime

Text Preprocessing:

Lowercasing

Cleaning special characters

Tokenization

Padding sequences

Loading the trained RNN model

Making Sentiment Prediction

📈 Output / Prediction
-------------------------
User enters a tweet in terminal

Model predicts and displays:

Positive 👍

or

Negative 👎

