# Public Relations Department Project

## 📌 Overview

This project applies **Natural Language Processing (NLP)** techniques to analyze customer reviews of Amazon Alexa products. The aim is to extract insights about public sentiment and feedback, helping the Public Relations department understand customer perceptions and improve engagement strategies.

## 📂 Project Structure

```
├── Public_Relations_png/                  # Visualizations from the analysis
├── Public_Relations_Department.ipynb      # Jupyter Notebook with full analysis and model building
├── amazon_alexa.tsv                       # Dataset containing Alexa product reviews                           
└── README.md                              # Project documentation
```

## 📊 Dataset

The dataset `amazon_alexa.tsv` includes customer reviews for Alexa products, with the following key features:

- **rating**: Customer's star rating (1-5)
- **date**: Date of the review
- **variation**: Product variant
- **verified_reviews**: Text of the customer's review
- **feedback**: Binary label indicating positive (`1`) or negative (`0`) sentiment

## 🚀 Installation

### 1️⃣ Clone the repository:

```
git clone https://github.com/ranjansinghds/Public-Relations-Department-Project.git 
cd Public-Relations-Department-Project
```

### 2️⃣ Install dependencies:
```
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

## 🔍 Methodology

### 1. **Data Preprocessing** 

* Cleaned text data (removed punctuation, stopwords, ect.)
* Tokenized and normalized review text
* Encoded categorical variables and labels

### 2. **Exploratory Data Analysis (EDA)**

* Analyzed rating distributions and sentiment trends
* Explored relationships between product variations and sentiment
* Visualized word frequencies using bar plots and word clouds

### 3. **Model Building**

- Implemented NLP classification models to predict feedback based on review content
- Used CountVectorizer and TF-IDF for feature extraction
- Applied Logistic Regression and Naive Bayes for sentiment prediction

### 4. **Model Evaluation**

- Evaluated models using metrics such as accuracy, precision, recall, F1-score
- Visualized results using confusion matrix and ROC curves

## 📊 Visualizations

Here are some visualizations from the project:

![alt text](https://github.com/ranjansinghds/Public-Relations-Department-Project/blob/main/Public%20Relations%20Department%20Project%20Png/barplot.png)
![alt text](https://github.com/ranjansinghds/Public-Relations-Department-Project/blob/main/Public%20Relations%20Department%20Project%20Png/countplot.png)
![alt text](https://github.com/ranjansinghds/Public-Relations-Department-Project/blob/main/Public%20Relations%20Department%20Project%20Png/wordcloud.png)

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy**
- **NLTK**
- **Scikit-learn**
- **Matplotlib & Seaborn**
- **Jupyter Notebook**

## 📌 Future Improvements

- Integrate more advanced NLP models like BERT for better performance
- Perform topic modeling to discover hidden themes in customer feedback
- Deploy the model as an API for real-time review analysis