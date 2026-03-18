# Sentiment Analysis: RNN (LSTM) vs. Naive Bayes 🤖💬

This project compares two different approaches to Natural Language Processing: 
1. **Probabilistic Modeling** (Naive Bayes)
2. **Deep Sequential Modeling** (LSTM/RNN)

## 🚀 Key Features
* **Dataset:** Used the [IMDB/Amazon] review dataset.
* **Preprocessing:** Tokenization, Stop-word removal, and Padding for LSTMs.
* **Comparison:** Evaluates Accuracy, Precision, and Training Time.

## 📊 Results Summary
| Model | Accuracy | Training Time | Handles Sarcasm? |
| :--- | :--- | :--- | :--- |
| Naive Bayes | 82% | < 1 sec | No |
| LSTM (RNN) | 89% | 15 mins | Partially |

## 🛠️ How to Run
1. Clone the repo: `git clone https://github.com/your-username/repo-name.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook notebooks/analysis.ipynb`
