# Twitter-Sentiment-Analysis
Data Science Internship Projects
## 📌 About This Project
This project analyzes and visualizes 
sentiment patterns in Twitter social 
media data to understand public opinion 
and attitudes towards specific topics 
and brands.
Built as Task 4 of my Data Science 
Internship at SAM AI Technologies.

## 🎯 Objective
Build a sentiment classification model
that predicts whether a tweet is
Positive, Negative or Neutral using
Natural Language Processing and
Machine Learning.

## 📊 Dataset
- Source: Kaggle Twitter Sentiment Dataset
- Training rows  : 74,682 (before cleaning)
- Training rows  : 59,119 (after cleaning)
- Validation rows: 1,000  (before cleaning)
- Validation rows: 828    (after cleaning)
- Features       : 4 columns
- Target         : Sentiment
  (Positive / Negative / Neutral)

## 📋 Dataset Columns
| Column    | Description              |
|-----------|--------------------------|
| id        | Unique tweet ID          |
| topic     | Brand or topic discussed |
| sentiment | Positive/Negative/Neutral|
| tweet     | Actual tweet text        |

## 🛠️ Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF Vectorizer
- WordCloud
- Google Colab

## 📋 Steps Completed

### Step 1 — Data Loading
- Loaded Training dataset
  (74,682 rows)
- Loaded Validation dataset
  (1,000 rows)
- Added proper column names

### Step 2 — Data Preprocessing
#### Training Dataset Fixes:
- Removed 2,700 duplicate rows
- Removed 686 missing tweet rows
- Removed 12,990 irrelevant rows
- Final clean rows: 59,119

#### Validation Dataset Fixes:
- Removed 172 irrelevant rows
- Final clean rows: 828

### Step 3 — Text Cleaning
- Converted text to lowercase
- Removed website links (http)
- Removed @mentions
- Removed hashtag symbols
- Removed numbers
- Removed extra spaces

### Step 4 — Data Visualization
- Chart 1: Sentiment Count Bar Chart
- Chart 2: Sentiment Pie Chart
- Chart 3: Top 10 Topics Bar Chart
- Chart 4: Positive Tweets WordCloud
- Chart 5: Negative Tweets WordCloud

### Step 5 — ML Model Building
- Used TF-IDF to convert text
  to numbers
- Applied Logistic Regression model
- Train size: 47,534 tweets
- Test size : 12,345 tweets

## ✅ Model Results
| Metric         | Score  |
|----------------|--------|
| Algorithm      | Logistic Regression |
| Accuracy       | 76.32% |
| Negative Precision | 76% |
| Positive Precision | 77% |
| Neutral Precision  | 75% |
| Train size     | 47,534 |
| Test size      | 12,345 |

## 📊 Sentiment Distribution
| Sentiment | Training Count |
|-----------|---------------|
| Negative  | 21,698        |
| Positive  | 19,713        |
| Neutral   | 17,708        |

## 📁 Files in This Repository
- Twitter_sentiment_Analysis.ipynb
  — Main notebook with all code
- twitter_training_dataset_csv.csv
  — Training dataset
- twitter_validation_dataset_csv.csv
  — Validation dataset

## 🏢 Internship Details
- Company  : SAM AI Technologies
- Domain   : Data Science
- Task     : Task 2
- Accuracy : 76.32%
