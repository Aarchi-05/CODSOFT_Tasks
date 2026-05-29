# CODSOFT_Tasks
# 🎬📩💳 Machine Learning Tasks Collection

### Movie Genre Classification | Credit Card Fraud Detection | SMS Spam Detection

This repository contains **three end-to-end Machine Learning projects** focused on solving real-world classification problems using **Natural Language Processing (NLP)** and **Traditional Machine Learning algorithms**.

Each project follows a complete ML workflow including:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training & Evaluation
* Visualization
* Model Comparison
* Final Prediction System

---

# 📌 Projects Included

## 1. 🎬 Movie Genre Classification

Build an intelligent movie genre prediction system that classifies movie plots into genres using **Natural Language Processing (NLP)** techniques.

### Problem Statement

Given a movie plot summary, predict the correct movie genre based on textual information.

### Dataset
Dataset: [Movie Genre Classification Dataset](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)
Movie plot dataset containing:

* Movie plot descriptions
* Corresponding genres

### Techniques Used

* Text Cleaning
* TF-IDF Vectorization
* Text Preprocessing
* Label Encoding
* Feature Extraction

### Models Implemented

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

### Hyperparameter Tuning

* GridSearchCV for SVM optimization

### Best Performing Model

✅ **Tuned SVM Classifier**

### Key Features

✔ NLP preprocessing
✔ TF-IDF feature extraction
✔ Multi-model comparison
✔ Hyperparameter tuning
✔ Genre prediction system

---

## 2. 💳 Credit Card Fraud Detection

A Machine Learning model to detect fraudulent credit card transactions using customer behavior, transaction patterns, timing, and location features.

### Problem Statement

Detect whether a transaction is:

```text
0 → Legitimate Transaction
1 → Fraudulent Transaction
```

### Dataset
Dataset: [Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
Fraud Detection Dataset from Kaggle:

* **fraudTrain.csv**
* **fraudTest.csv**

Contains:

* Transaction amount
* Merchant category
* Customer information
* Geographic coordinates
* Transaction timestamps
* Fraud labels

### Feature Engineering

Custom features were created to improve model performance:

* Transaction Hour
* Day of Week
* Customer Age
* Geographic Distance
* Transaction Timing Features

### Models Implemented

* Logistic Regression
* Decision Tree
* Random Forest

### Best Performing Model

✅ **Random Forest Classifier**

### Performance

| Metric          | Score      |
| --------------- | ---------- |
| Accuracy        | **98.98%** |
| ROC-AUC         | **0.990**  |
| Fraud Recall    | **88%**    |
| Fraud Precision | **26%**    |

### Workflow

```text
Raw Transaction Data
         ↓
Data Cleaning
         ↓
Feature Engineering
         ↓
Encoding & Scaling
         ↓
Model Training
(LR / DT / RF)
         ↓
Performance Evaluation
         ↓
Fraud Prediction
```

### Key Features

✔ Imbalanced data handling
✔ Feature engineering
✔ Geographic distance calculation
✔ Multiple model comparison
✔ Fraud probability prediction
✔ Feature importance analysis

---

## 3. 📩 SMS Spam Detection

An NLP-based spam classifier that predicts whether an SMS message is spam or legitimate using **TF-IDF vectorization** and machine learning classifiers.

### Problem Statement

Classify messages into:

```text
ham  → Legitimate Message
spam → Spam Message
```

### Dataset
Dataset: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
SMS Spam Collection Dataset containing:

* **5572 SMS messages**
* Ham messages
* Spam messages

### Text Preprocessing

The following NLP preprocessing steps were performed:

* Lowercasing
* Stopword Removal
* Punctuation Removal
* Tokenization
* Stemming

### Feature Extraction

* TF-IDF Vectorization

### Models Implemented

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

### Best Performing Model

✅ **Support Vector Machine (SVM)**

### Performance

| Metric      | Score      |
| ----------- | ---------- |
| Accuracy    | **98.65%** |
| Spam Recall | **91%**    |
| Precision   | **99%**    |
| F1 Score    | **95%**    |

### Workflow

```text
Raw SMS Message
        ↓
Text Cleaning
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Model Training
(NB / LR / SVM)
        ↓
Spam Prediction
```
### Key Features

✔ NLP preprocessing pipeline
✔ WordCloud visualization
✔ Frequent word analysis
✔ ROC curve comparison
✔ Multi-model evaluation
✔ Final prediction system

---

# 📊 Visualizations Included

The repository contains several visualizations for better understanding of the datasets and model performance.

### Movie Genre Classification

* Genre distribution
* Model performance comparison
* Confusion matrix

### Credit Card Fraud Detection

* Fraud vs Legit distribution
* Transaction amount analysis
* Feature importance graph
* Confusion matrices

### SMS Spam Detection

* Spam vs Ham distribution
* Word Clouds
* Message length analysis
* Top spam words
* ROC Curve comparison
* Confusion matrices

---

# 🧠 Machine Learning Pipeline

All projects follow a structured ML pipeline:

```text
Data Collection
        ↓
Data Cleaning
        ↓
EDA & Visualization
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Hyperparameter Tuning
        ↓
Final Prediction System
```

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* WordCloud
* Pickle

### Machine Learning Algorithms

* Logistic Regression
* Naive Bayes
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

### NLP Techniques

* TF-IDF Vectorization
* Stemming
* Stopword Removal
* Tokenization

---

# 📂 Repository Structure

```text
CODSOFT_Tasks/
│── Movie_Genre_Classification/
│   ├── Task1.ipynb
│   ├── dataset/
│   └── screenshots/
│
│── Credit_Card_Fraud_Detection/
│   ├── Task2.ipynb
│   ├── dataset/
│   └── saved_model/
│
│── SMS_Spam_Detection/
│   ├── Task3.ipynb
│   ├── dataset/
│   └── saved_model/
│
│── README.md
│── requirements.txt
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Aarchi-05/your-repo-name.git
```

Navigate to the project folder:

```bash
cd your-repo-name
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📦 Required Dependencies

Install manually:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud
```

---


# 🚀 Future Improvements

Possible future enhancements:

### Movie Genre Classification

* Deep Learning models (LSTM, BERT)
* Multi-label genre classification
* Genre confidence score

### Fraud Detection

* XGBoost / LightGBM
* Real-time fraud detection API
* SMOTE for imbalance handling
* Deep anomaly detection

### SMS Spam Detection

* BERT-based spam detection
* Real-time SMS filtering system
* Explainable AI predictions

---

# 📈 Results Summary

| Project                     | Best Model    | Accuracy         |
| --------------------------- | ------------- | ---------------- |
| Movie Genre Classification  | Tuned SVM     | **59.09%** |
| Credit Card Fraud Detection | Random Forest | **98.98%**       |
| SMS Spam Detection          | SVM           | **98.65%**       |

---

# 👩‍💻 Author

**Aarchi Jain**
AIML Undergraduate Student | Machine Learning & AI Enthusiast

If you found this repository useful, consider giving it a ⭐
