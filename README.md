# 📧 SMS Spam Detection using NLP

This project applies Natural Language Processing techniques to classify SMS messages as **spam** or **ham** (not spam), using the Multinomial Naive Bayes algorithm and TF-IDF vectorization.

## 📂 Project Structure
- `data/`: Dataset or download instructions.
- `notebooks/`: Main Jupyter notebook used for training and evaluation.
- `src/`: (Optional) Python scripts for preprocessing and modeling.
- `results/`: Visual results like confusion matrix and performance plots.
- `README.md`: Project summary and how to run the code.
- `requirements.txt`: Required Python packages.

## 🧠 Methodology
- Preprocessing: Lowercasing, tokenization, stopword removal, lemmatization
- Feature Engineering: Message length
- Feature Extraction: TF-IDF (unigrams and bigrams)
- Model: Multinomial Naive Bayes

## 📊 Performance
- **Accuracy**: 97.8% on the test set
- **Precision (spam)**: 97%
- **Recall (spam)**: 85%
- **F1-score (spam)**: 90%

## 📁 Dataset
Dataset used: [UCI SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

## ▶️ Run the Code

1. Clone the repo:
```bash
git clone https://github.com/yourusername/spam-detection-nlp.git
cd spam-detection-nlp
