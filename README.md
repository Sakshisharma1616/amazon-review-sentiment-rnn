# 🧠 Amazon Review Sentiment Analysis using RNN (TensorFlow & Keras)

This project performs sentiment analysis on Amazon product reviews using a Recurrent Neural Network (RNN) implemented with TensorFlow and Keras. The goal is to predict the review rating (1 to 5 stars) based on the review text, leveraging NLP techniques and deep learning.

---

## 📌 Features

- 🔄 Text preprocessing: cleaning, tokenization, and padding
- 🔢 Word embedding and sequence preparation
- 🔁 RNN model built using Keras (with `SimpleRNN`)
- 📊 Evaluation on test data
- 🧪 Custom input sentiment prediction

---

## 🧑‍💻 Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Natural Language Processing (NLP)
- Jupyter Notebook

---

## 📁 Project Structure


├── data/ # Folder for dataset (CSV or text)
├── rnn_az_senti_analysis.ipynb # Main notebook with code and results
├── requirements.txt # List of Python dependencies
└── README.md # Project documentation


---

## 🚀 Getting Started

### 1. Clone the Repository
git clone https://github.com/TravelXML/TENSORFLOW-AND-KERAS-SENTIMENT-ANALYSIS-USING-RNN.git
cd TENSORFLOW-AND-KERAS-SENTIMENT-ANALYSIS-USING-RNN

### 2. **Create a Virtual Environment (optional)**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install Requirements
pip install -r requirements.txt

###4. Open Jupyter Notebook
jupyter notebook rnn_az_senti_analysis.ipynb
