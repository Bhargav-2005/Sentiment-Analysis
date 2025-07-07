# Sentiment Analysis on Product Reviews

This project focuses on performing sentiment analysis on customer reviews using natural language processing (NLP) and machine learning techniques. It classifies the sentiment of reviews into **positive**, **negative**, or **neutral** based on the text content.

## 📁 Files

- **`Reviews.csv`**: A dataset containing customer reviews and their ratings.
- **`SentimentAnalysis.ipynb`**: A Jupyter Notebook that walks through data exploration, preprocessing, sentiment classification, model training, and evaluation.

## 🧾 Dataset Overview

The dataset includes:
- **Review Text**: The written review provided by the customer.
- **Rating**: A numerical rating (e.g., 1 to 5 stars).

### Sentiment Mapping
Ratings are mapped to sentiments as follows:
- **1-2**: Negative
- **3**: Neutral
- **4-5**: Positive

###📚 Libraries Used
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn
  - nltk, wordcloud



## 🔍 Project Steps

1. **Exploratory Data Analysis (EDA)**  
   - Distribution of ratings and sentiment classes  
   - Word frequency analysis  
   - Word clouds

2. **Text Preprocessing**  
   - Lowercasing  
   - Stopword removal  
   - Punctuation cleaning  
   - Stemming or lemmatization

3. **Feature Extraction**  
   - Bag-of-Words  
   - TF-IDF

4. **Model Building**  
   - Logistic Regression  
   - Naive Bayes  
   - Support Vector Machine (SVM)  

5. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix

## 📈 Results

The notebook compares multiple models and identifies the best-performing approach based on the evaluation metrics. Insights from the data are also visualized through plots and word clouds.

## 🛠️ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
