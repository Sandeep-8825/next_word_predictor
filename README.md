# next_word_predictor
# 🔮 Next Word Predictor (LSTM)

This project is a **Next Word Prediction Web App** built using an LSTM model and deployed with Streamlit.

## 🚀 Features

* Predicts the next word based on user input
* Uses trained LSTM model
* Simple and clean UI with Streamlit

## 🧠 Tech Stack

* Python
* TensorFlow / Keras
* Streamlit
* NumPy
* Pickle

## 📁 Project Structure

```
project/
│
├── app.py
├── model.h5
├── tokenizer.pickle
├── max_len.pickle
├── requirements.txt
└── README.md
```

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/your-username/next-word-predictor.git
cd next-word-predictor
```

2. Install dependencies:

```
pip install -r requirements.txt
```

## ▶️ Run the App

```
streamlit run app.py
```

## 📌 How It Works

* Input text is tokenized using a saved tokenizer
* Sequence is padded to match training length
* LSTM model predicts the next word

## 📸 Demo

Type a sentence → Click Predict → Get next word

## 🤝 Contributing

Feel free to fork and improve the project!

## 📜 License

This project is open-source.
