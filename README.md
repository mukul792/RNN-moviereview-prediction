# 🎬 IMDB Movie Review Sentiment Analysis using Simple RNN

This project builds a **Deep Learning model** using **Simple Recurrent Neural Network (RNN)** to classify IMDB movie reviews as **positive** or **negative**.  
It demonstrates the use of **word embeddings**, **sequence padding**, and **RNN layers** for text sentiment classification.

---

## 🚀 Project Overview
- **Objective:** Predict sentiment (positive/negative) of movie reviews.
- **Dataset:** IMDB dataset (from `tensorflow.keras.datasets`).
- **Model:** Simple RNN built using Keras Sequential API.
- **Activation:** ReLU (RNN), Sigmoid (Output).
- **Optimizer:** Adam.
- **Loss Function:** Binary Crossentropy.

---

## 🧠 Workflow  
1. Load the IMDB dataset.  
2. Preprocess and pad the sequences.  
3. Build a Sequential RNN model.  
4. Compile using Adam and binary crossentropy.  
5. Train with EarlyStopping.  
6. Evaluate model performance.  
7. Save the trained model.

