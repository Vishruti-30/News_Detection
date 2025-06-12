# 📰 Fake News Detection with Logistic Regression

A text classification project using **Logistic Regression** to detect whether a news article is **real or fake** based on its textual content. This project uses a publicly available dataset from Kaggle and is implemented in Python using `scikit-learn` and `TF-IDF` vectorization.

---

## 📁 Project Structure

```
├── fake_news_detection.ipynb # Jupyter notebook with complete code and analysis
├── Fake.csv # Fake news articles (from Kaggle dataset)
├── True.csv # Real news articles (from Kaggle dataset)
├── README.md # Project documentation (this file)
```

---

## 🎯 Project Objectives

- Learn how to apply **Logistic Regression** for text classification  
- Preprocess and clean textual data using **TF-IDF**  
- Train a model to classify news as **fake (0)** or **real (1)**  
- Evaluate model performance using metrics like **accuracy**, **precision**, **recall**, and **F1-score**  
- Make predictions on new, unseen text samples

---

## 🔍 Dataset Overview

Dataset used:  
👉 [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

**Dataset Details:**

| File      | Description                        |
|-----------|------------------------------------|
| `Fake.csv` | Contains fake news headlines/articles |
| `True.csv` | Contains real news headlines/articles |

We combined the `title` and `text` columns into a single `content` field and labeled:
- `0` = Fake
- `1` = Real

---

## 📊 Sample Output

Accuracy: 93.4%  
Precision (Fake): 0.94  
Recall (Fake): 0.93  
F1 Score (Fake): 0.93

---


## 🧠 Key Takeaways

- TF-IDF is an effective technique to convert textual data into meaningful numerical features.
- Logistic Regression is a simple yet powerful algorithm for binary text classification.
- Clean and well-labeled data significantly improves model performance.
- Text preprocessing (e.g., combining title and body, removing nulls) is crucial for NLP tasks.
- Even with basic models, high accuracy is achievable with proper data handling and feature extraction.

---

## 📌 Requirements

- Python 3.x  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn
