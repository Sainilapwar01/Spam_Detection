
# 📩 Spam Detection using Machine Learning

A machine learning project that classifies SMS messages as **spam** or **ham** using Natural Language Processing and various ML models.

---

## 📁 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 🧠 Overview
This project demonstrates a full machine learning pipeline for spam detection:
- Data cleaning and preprocessing
- Feature extraction using Bag-of-Words
- Model training and evaluation
- Comparison between Naive Bayes, SVM, Logistic Regression, and Random Forest

---

## 📊 Dataset
The dataset used is a collection of SMS messages labeled as `spam` or `ham`.  
It includes fields like:
- **label** – indicates whether the message is spam or ham  
- **message** – the actual content of the SMS

Source: [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

---

## 🛠 Technologies Used
- Python
- pandas, numpy
- sklearn
- nltk
- matplotlib, seaborn (for visualization)
- Jupyter Notebook

---

## 🛠 Installation
Clone the repo:
```bash
git clone https://github.com/your-username/spam-detection.git
cd spam-detection
```

Install the required packages:
```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run
1. Open the Jupyter Notebook:
```bash
jupyter notebook spam_detection.ipynb
```
2. Run all the cells to see preprocessing, model training, and evaluation.

---

## 📈 Results
| Model               | Accuracy |
|--------------------|----------|
| Naive Bayes        | ~97%     |
| Logistic Regression| ~96%     |
| SVM                | ~95%     |
| Random Forest      | ~96%     |

Naive Bayes performed the best due to its effectiveness in handling text data.



