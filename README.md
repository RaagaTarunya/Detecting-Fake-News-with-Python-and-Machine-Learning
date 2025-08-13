# Detecting-Fake-News-with-Python-and-Machine-Learning
# 📰 Fake News Detection with Python and Machine Learning  

## 📌 Overview  
This project builds a machine learning model to detect fake news articles using **Natural Language Processing (NLP)** and **scikit-learn**.  
The model processes and vectorizes news article text using **TF-IDF**, then trains a **Passive Aggressive Classifier** to distinguish between fake and real news.  

**Key Achievements:**  
- **93% accuracy** in detecting fake news on test data.  
- Preprocessed and vectorized over **20,000 articles**.  
- Evaluated using **confusion matrix** and accuracy metrics.  

---

## 📂 Dataset  
- Source: `news.csv` (contains labeled real and fake news articles)  
- Columns:  
  - `title` — Headline of the article  
  - `text` — Main content of the article  
  - `label` — `FAKE` or `REAL`  

---

## 🛠️ Tools & Libraries  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, scikit-learn  
- **NLP Techniques:** TF-IDF Vectorization, Stopword Removal  

---

## ⚙️ Installation  
```bash
# Clone the repository
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection

# Install dependencies
pip install -r requirements.txt
