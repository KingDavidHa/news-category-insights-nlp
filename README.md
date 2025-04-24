#  News Category Classification with NLP & ML

A comprehensive end-to-end NLP project for classifying news articles into categories using classic ML models and deep learning (LSTM, BERT). Built with a dataset of 200K+ real-world headlines from HuffPost.

---

##   Dataset
- **Source:** [HuffPost News Category Dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset)
- **Size:** 209,527 news articles  
- **Features:** `headline`, `short_description`, `category`, `authors`, `date`, `link`

---

##   Exploratory Data Analysis (EDA)
- Category distribution
- Headline length statistics
- Yearly trends for top 10 categories
- Missing value & duplication analysis

---

##   Preprocessing
- Custom text cleaning, stopword removal, lemmatization
- TF-IDF vectorization (10K features)
- Train/Test split (80/20 stratified)

---

##   Models Trained
| Model               | Accuracy |
|--------------------|----------|
| Naive Bayes         | 51.9%    |
| Logistic Regression | 59.6%    |
| SVM (LinearSVC)     | 59.0%    |
| LSTM (Bidirectional) | **59.4%** |
| BERT (Sampled only) | –        |

---

##   Keyword Insights
Top keywords extracted per category using Logistic Regression coefficients for SEO & editorial strategy.

---

##   Business Insights
1. **Category Imbalance:** Some categories appear 35x more than others.
2. **Headline Length Strategy:** U.S. News has the longest; Food & Drink the shortest.
3. **Trend-based Recommendations:** Focus content planning on growing categories.
4. **AI-Powered Suggestions:** Auto-tagging, SEO optimization, content generation.

---

##   Future Enhancements
- Fine-tuned BERT with full dataset
- Deployment as real-time API
- Dashboard using Streamlit or Plotly Dash

---
