<!-- HERO -->

<h1 align="center">📩 SMS Spam Detection System 🚀</h1>

<p align="center">
  <b>End-to-End NLP Pipeline with Advanced Model Benchmarking</b><br>
  Built for high-precision spam detection using Machine Learning
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/NLP-TF--IDF-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ML-ScikitLearn-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/UI-Streamlit-red?style=for-the-badge&logo=streamlit"/>
  <img src="https://img.shields.io/badge/Status-ProductionReady-brightgreen?style=for-the-badge"/>
</p>

---

# 🎬 Demo

<p align="center">
  <img src="assets/demo.gif" width="650"/>
</p>

> ⚡ Real-time spam classification powered by optimized ML pipeline

---

# 🧠 Problem Statement

SMS spam is a **real-world classification problem** with challenges such as:

* Noisy text data
* High class imbalance
* Context-dependent semantics
* Need for high precision (false positives are costly)

👉 This project builds a **robust, production-oriented solution** to detect spam messages.

---

# 🚀 Solution Overview

### 🔄 Pipeline

```text
Raw Text
   ↓
Text Cleaning & Normalization
   ↓
Tokenization (NLTK)
   ↓
Stopword Removal + Stemming
   ↓
TF-IDF Vectorization
   ↓
Model Training (Multiple Algorithms)
   ↓
Evaluation & Comparison
   ↓
Prediction
```

---

# 🔬 Feature Engineering

The model performance heavily relies on preprocessing:

✔ Lowercasing
✔ Tokenization (`nltk.word_tokenize`)
✔ Removal of non-alphanumeric tokens
✔ Stopword filtering
✔ Stemming (PorterStemmer)
✔ TF-IDF transformation

---

# 📊 Dataset Insights

* Dataset: SMS Spam Collection
* Labels:

  * `ham` → legitimate message
  * `spam` → unwanted message

### 🧠 Engineered Features

* Message length
* Word count
* Sentence count
* TF-IDF features

---

# ⚙️ Models Implemented

This project does **extensive benchmarking** across multiple ML algorithms:

| Category       | Models                        |
| -------------- | ----------------------------- |
| Linear         | Logistic Regression           |
| Probabilistic  | Naive Bayes                   |
| Tree-based     | Decision Tree, Random Forest  |
| Ensemble       | Bagging, AdaBoost, ExtraTrees |
| Boosting       | XGBoost, Gradient Boosting    |
| Kernel-based   | SVC                           |
| Instance-based | KNN                           |

---

# 📈 Model Performance (Real Results)

## 🏆 Top Performing Models

| Rank | Model         | Accuracy   | Precision  | F1 Score   |
| ---- | ------------- | ---------- | ---------- | ---------- |
| 🥇   | **SVC**       | **0.9027** | **0.9758** | **0.9748** |
| 🥈   | Extra Trees   | 0.8984     | 0.9748     | 0.9745     |
| 🥉   | Random Forest | 0.8932     | 0.9738     | **0.9826** |

---

## 📊 Full Comparison

| Model    | Accuracy | Precision | F1         |
| -------- | -------- | --------- | ---------- |
| SVC      | 0.9027   | 0.9758    | 0.9748     |
| ETC      | 0.8984   | 0.9748    | 0.9745     |
| RF       | 0.8932   | 0.9738    | **0.9826** |
| NB       | 0.8780   | 0.9709    | **1.0000** |
| XGB      | 0.8705   | 0.9680    | 0.9487     |
| Bagging  | 0.8389   | 0.9584    | 0.8682     |
| LR       | 0.8067   | 0.9555    | 0.9600     |
| GBDT     | 0.7866   | 0.9506    | 0.9306     |
| DT       | 0.6974   | 0.9303    | 0.8300     |
| AdaBoost | 0.6431   | 0.9216    | 0.8202     |
| KNN      | 0.4494   | 0.9052    | 1.0000     |

---

# 🧠 Key Observations (Important)

### 🔹 1. SVC dominates overall performance

* Best balance of accuracy + precision + F1
* Works well with high-dimensional TF-IDF vectors

---

### 🔹 2. Random Forest has highest F1 stability

* Strong generalization
* Handles feature interactions well

---

### 🔹 3. Naive Bayes achieves perfect recall (F1 = 1.0)

* But slightly lower accuracy
* Sensitive to data distribution

---

### 🔹 4. KNN performs poorly

* Not suitable for high-dimensional sparse text data
* Computationally expensive

---

# 📊 Visualization

## Model Comparison

<p align="center">
  <img src="assets/model_comparison.png" width="550"/>
</p>

---

## Confusion Matrix (Best Model)

<p align="center">
  <img src="assets/confusion_matrix.png" width="400"/>
</p>

---

# 🧠 Why This System Works

### 💡 Key Insight

> Text classification is best handled by models that can work with **sparse, high-dimensional data**

---

### ✔ Why SVC works:

* Maximizes margin → better generalization
* Handles sparse TF-IDF efficiently

---

### ✔ Why TF-IDF:

* Captures word importance
* Reduces noise from common words

---

# 🌐 Live Deployment

👉 https://your-app-url.streamlit.app

---

# ▶️ Run Locally

```bash
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier
pip install -r requirements.txt
streamlit run app.py
```

---

# 📂 Project Structure

```text
sms-spam-classifier/
│
├── data/
├── model/
│   ├── vectorizer.pkl
│   ├── model.pkl
│
├── app.py
├── train.py
├── requirements.txt
└── README.md
```

---

# 🔮 Future Improvements

* 🤖 Transformer models (BERT, DistilBERT)
* 📱 Mobile-friendly UI
* 🌍 Multilingual spam detection
* ⚡ Real-time API (FastAPI)

---

# 🧠 Interview Explanation (🔥 USE THIS)

> “I built a spam classifier using TF-IDF and evaluated multiple ML models.
> SVC performed best because it handles high-dimensional sparse data effectively.
> I also engineered features like message length and compared models using precision, recall, and F1-score.”

---

# ⭐ Support

If you found this useful:

👉 Give it a ⭐ on GitHub

---

<p align="center">
  Built with ❤️ by Ishank Mishra
</p>
