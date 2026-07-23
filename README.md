# 📰 Fake News Classification using Attention-Based BiLSTM

An NLP-based Deep Learning project that classifies news articles as **Fake** or **Real** using an **Attention-Based Bidirectional LSTM (BiLSTM)** model. The project includes text preprocessing, model training, evaluation, and prediction on custom news articles.

---

## 📌 Project Overview

Fake news spreads rapidly through social media and online platforms. This project aims to automatically detect fake news articles using Natural Language Processing (NLP) and Deep Learning techniques.

The model preprocesses news text, converts it into numerical representations, and uses an Attention-Based BiLSTM network to capture contextual information for accurate classification.

---

## ✨ Key Features

- NLP-based text preprocessing
- Stopword removal and lemmatization
- Tokenization and sequence padding
- Attention-Based Bidirectional LSTM model
- 5-Fold Stratified Cross Validation
- Early Stopping & Learning Rate Scheduling
- Model evaluation using multiple performance metrics
- Prediction on custom news articles
- Model and tokenizer saving for future inference

---

## 📂 Repository Structure

```
fake_news_classification_project/
│
├── Fake_News_Classification_Project.ipynb
├── README.md
```

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- KaggleHub

---

## 📊 Workflow

1. Import required libraries
2. Load Fake & Real News Dataset
3. Clean and preprocess text
4. Tokenize news articles
5. Pad input sequences
6. Build Attention-Based BiLSTM model
7. Train model
8. Evaluate performance
9. Predict custom news
10. Save trained model

---

## 🧠 Model Architecture

```
Input Text
     │
Embedding Layer
     │
BiLSTM (64 Units)
     │
BiLSTM (32 Units)
     │
Attention Layer
     │
Dense Layer
     │
Dropout
     │
Sigmoid Output
```

---

## 📈 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/PurvikTaneja/fake_news_classification_project.git
```

Move into the project directory

```bash
cd fake_news_classification_project
```

Install dependencies

```bash
pip install tensorflow pandas numpy matplotlib seaborn nltk scikit-learn kagglehub
```

Open the notebook

```bash
jupyter notebook Fake_News_Classification_Project.ipynb
```

---

## 📁 Dataset

Dataset Used:

**Fake and Real News Dataset**

Contains:

- Fake.csv
- True.csv

Each article is classified into one of two categories:

- Fake News
- Real News

---

## 🔮 Future Improvements

- BERT / RoBERTa implementation
- Streamlit web application
- Real-time fake news detection
- Explainable AI using SHAP/LIME
- Hyperparameter optimization

---

## 👨‍💻 Author

**Purvik Taneja**

B.Tech Electrical & Electronics Engineering  
Minor Specialization in Artificial Intelligence & Machine Learning

**Areas of Interest**

- Machine Learning
- Deep Learning
- Natural Language Processing
- Artificial Intelligence

---

## ⭐ If you found this project useful, consider giving it a star!
