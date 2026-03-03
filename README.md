# 🧠 Mental Health Detection Using Social Media Text Analysis

---

## 📌 Project Objective

Analyze social media text data to detect early signs of mental health conditions such as depression, anxiety, and stress using Natural Language Processing (NLP) and machine learning techniques.

---

## 🧠 Problem Statement

Mental health issues often go undetected due to lack of early screening mechanisms.  
This project aims to analyze user-generated social media posts, identify linguistic patterns associated with mental health conditions, and develop predictive models for early detection and proactive intervention.

---

## 📊 Dataset Description

The dataset includes:

- statement (User-generated social media post)
- status (Mental health category label)
- text_length (Character length of post)
- word_count (Number of words in post)

**Total Records:** Multiple labeled text samples across mental health categories.

---

## 🛠 Tools & Technologies Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- MySQL
- Power BI

---

## 🔎 Step 1: Data Cleaning

- Handled missing values in text data
- Standardized dataset structure
- Engineered additional features:
  - Text Length
  - Word Count
- Saved cleaned dataset (`cleaned_mh.csv`)

---

## 📈 Step 2: Exploratory Data Analysis (EDA)

Performed:

- Mental health status distribution analysis
- Text length distribution study
- Word count distribution analysis
- Status vs text length comparison
- Status vs word count comparison
- Text length vs word count correlation study
- Correlation heatmap for numerical features

This helped identify linguistic variation across mental health categories.

---

## 🤖 Step 3: Predictive Modeling

### 📌 Logistic Regression (Multi-class Classification)

**Target Variable:**  
status (Depression / Anxiety / Stress / etc.)

**Text Processing Technique:**  
TF-IDF Vectorization (max_features = 5000, English stopwords removed)

**Evaluation Metrics:**  
- Accuracy
- Confusion Matrix
- Classification Report
- ROC Curve (Multi-class)

**Objective:**  
Classify social media posts into mental health categories based on textual patterns.

---

## 🗄 Step 4: Database Integration

- Designed MySQL database schema (`mental_health`)
- Created `mental_h` table structure
- Inserted cleaned dataset into MySQL
- Enabled SQL-based querying for category-wise analysis

---

## 📊 Step 5: Power BI Dashboard

Created an interactive dashboard including:

- Mental health category distribution
- Average text length by category
- Word count comparison
- Category-wise trend analysis
- Data-driven insights visualization

**Dashboard File:**  
Located in `/dashboard/mental_health_dashboard.pbix`

---

## 📌 Key Business Insights

- Depressive posts tend to have higher word counts, indicating deeper emotional expression.
- Text length and word count show strong positive correlation.
- Anxiety-related posts display higher variability in length.
- Logistic Regression effectively classifies mental health categories using textual features.
- NLP-based models can support early detection and proactive mental health intervention.

---

## 🚀 Future Enhancements

- Integration of advanced NLP techniques (Lemmatization, N-grams)
- Implementation of Deep Learning models (LSTM, BERT)
- Real-time social media API integration
- Deployment as a web-based early detection system
- Sentiment intensity scoring for severity prediction

---

## 📂 Project Structure

Mental-Health-Social-Media-Analysis/  
│  
├── data/  
├── notebooks/  
├── database/  
├── dashboard/  
├── requirements.txt  
└── README.md  

---

## ▶ How to Run the Project

1. Clone the repository  
2. Install required libraries
3. Open `notebooks/mentall_healthh.ipynb`  
4. Run all cells  

5. Run `database/mysql_schema.sql` in MySQL Workbench before executing database insertion cells.

---

## 🎯 Project Impact

This project demonstrates the complete data analytics lifecycle:

- Data Cleaning  
- Exploratory Data Analysis  
- NLP Feature Engineering  
- Machine Learning Modeling  
- ROC Curve Evaluation  
- SQL Integration  
- Business Insights Generation  
- Interactive Dashboard Creation  

The analysis highlights how data-driven NLP models can assist in early mental health risk detection and support timely intervention strategies.
