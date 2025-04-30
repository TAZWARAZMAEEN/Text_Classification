# 🛡️ Cyberbullying Tweet Classification

A machine learning project for detecting and classifying cyberbullying in tweets using natural language processing (NLP). The dataset includes various types of bullying such as gender-based, religious, ethnic, age-related, and more.

---

## 📌 Project Overview

This project leverages Python and key data science libraries to analyze Twitter data and build a text classification model. The aim is to automatically classify tweets into one of the following categories:

- `not_cyberbullying`
- `gender`
- `religion`
- `age`
- `ethnicity`
- `other_cyberbullying`

---

## 📂 Dataset

The dataset (`cyberbullying_tweets.csv`) includes:

| Column              | Description                                             |
|---------------------|---------------------------------------------------------|
| `tweet_text`        | Raw tweet content                                       |
| `cyberbullying_type`| Type of cyberbullying or 'not_cyberbullying'            |

Example:
Tweet: "@XochitlSuckkks is a classy whore?"
Label: not_cyberbullying


---

## 🧰 Technologies Used

- **Python 3**
- **pandas**, **numpy** – Data handling
- **nltk**, **re** – Text preprocessing
- **matplotlib**, **seaborn** – Visualization
- **scikit-learn** – ML model training & evaluation

---

## 🔧 Features & Workflow

1. **Text Preprocessing**
   - Lowercasing, punctuation removal, lemmatization, stop word filtering
2. **Exploratory Data Analysis (EDA)**
   - Tweet length distributions, type counts, word clouds
3. **Model Building**
   - Vectorization using TF-IDF
   - Classifier: Logistic Regression
4. **Model Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-Score

---

## 🚀 Getting Started

### 🔨 Installation

Install all required dependencies with:

```bash
pip install -r requirements.txt

## 🧰 Technologies Used

- **Python 3**
- **pandas**, **numpy** – Data handling
- **nltk**, **re** – Text preprocessing
- **matplotlib**, **seaborn** – Visualization
- **scikit-learn** – ML model training & evaluation

---

## 🔧 Features & Workflow

1. **Text Preprocessing**
   - Lowercasing, punctuation removal, lemmatization, stop word filtering
2. **Exploratory Data Analysis (EDA)**
   - Tweet length distributions, type counts, word clouds
3. **Model Building**
   - Vectorization using TF-IDF
   - Classifier: Logistic Regression
4. **Model Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-Score

---

## 🚀 Getting Started

### 🔨 Installation

Install all required dependencies with:

```bash
pip install -r requirements.txt

📁 Clone and Run

git clone https://github.com/yourusername/cyberbullying-detection.git
cd cyberbullying-detection
jupyter notebook

📊 Results Snapshot
Accuracy: ~88%

Top Model: Logistic Regression

Most Common Bullying Type: gender

🤝 Collaborators
Mohammed Tazwar Islam – s3983534@student.emt.edu.au

📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.
