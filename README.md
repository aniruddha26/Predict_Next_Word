# Predicting Next Word using LSTM

This project demonstrates a **Deep Learning-based Next Word Prediction Model** using Long Short-Term Memory (LSTM) networks. The model predicts the next word in a given sequence of words and is deployed as an interactive Streamlit web application.

---

## 📖 Project Description

### 🔎 Overview
The goal of this project is to build a Natural Language Processing (NLP) model capable of predicting the next word in a sentence. The project leverages the power of **LSTMs**, which are well-suited for sequential data tasks such as text generation.

---

## ⚙️ Workflow

1. **Data Collection**
   - The dataset is based on Shakespeare's *Hamlet*.  
   - This complex and rich text provides a challenging dataset for sequence modeling.

2. **Data Preprocessing**
   - Tokenization of text into words.
   - Conversion into sequences and padding to ensure uniform input length.
   - Splitting data into training and testing sets.

3. **Model Building**
   - An **Embedding layer** for word representation.
   - Two **LSTM layers** for capturing sequential dependencies.
   - A **Dense output layer** with **Softmax activation** to predict the probability distribution of the next word.

4. **Model Training**
   - Training on prepared sequences.
   - **Early Stopping** implemented to avoid overfitting by monitoring validation loss.

5. **Model Evaluation**
   - Tested on example sentences to check next word prediction performance.

6. **Deployment**
   - A **Streamlit web application** is built where users can input a sequence of words and get real-time predictions for the next word.

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Numpy, Pandas**
- **NLTK / Tokenizer**
- **Streamlit** (for deployment)

---

## 🚀 Getting Started

### Clone the Repository

git clone https://github.com/aniruddha26/Predict_Next_Word.git

### Install Dependencies

pip install -r requirements.txt

### Run the Streamlit App

streamlit run app.py

## 📊 Results
The model learns sequential patterns from Hamlet.

Provides word-level predictions for given input text.

Interactive Streamlit app demonstrates predictions in real time.

## 👨‍💻 Author
Aniruddha Alkari

## 📌 Disclaimer
This project is created for educational and practice purposes only. It is not optimized for production use.