# detection_future_mental_disorders_ml-ensemble-llm
RTRP Project of batch 7 
# 🧠 Social Media as a Mirror: Mental Health Detection from Social Media Posts

This project presents a machine learning-based web application that detects **mental health conditions**—such as depression or suicidal tendencies—from **social media posts** using Natural Language Processing (NLP) techniques and multiple classification models.

It serves as a powerful tool for early detection of psychological risks through text analysis, enabling preventive mental health support.

---

## 🚀 Features

- 📝 Analyze social media text and detect mental health condition (Depression / No Depression)
- 🔍 NLP-based text preprocessing (stopword removal, lemmatization, tokenization)
- 🤖 Multiple classification models: Random Forest, SVM, Naive Bayes, Logistic Regression, Decision Tree
- 📊 Real-time accuracy & performance visualization
- 👤 User registration & login system
- 📂 Admin panel for model training & viewing predictions
- 📉 Confusion matrix, F1-score, Precision, Recall for model evaluation

---

## 🧰 Tech Stack

| Layer        | Technology |
|--------------|------------|
| Framework    | Django 3.x |
| Frontend     | HTML, CSS, Bootstrap |
| Backend      | Python 3.x |
| ML Libraries | scikit-learn, pandas, numpy |
| NLP          | NLTK |
| Database     | SQLite3 (default Django DB) |

---

## 🏗️ Project Structure

---

## 🧪 How It Works

1. **User Registration & Login**  
   Users register and log in to submit posts for analysis.

2. **Data Upload & Preprocessing**  
   Admin uploads a dataset of labeled posts. NLP preprocessing is performed.

3. **Model Training**  
   The system trains multiple ML models on the dataset and selects the best-performing model.

4. **Prediction**  
   Users input a social media message. The trained model classifies it as:
   - **No Depression**
   - **Depression**

5. **Admin Dashboard**  
   Admin can:
   - View uploaded posts
   - Analyze prediction ratios
   - Download results
   - View accuracy charts

---

## 📦 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/social-media-as-a-mirror.git
cd social-media-as-a-mirror


