# 🎬 Movie Recommender System (ML + NLP)

A **content-based movie recommendation system** built with Natural Language Processing (NLP) and Machine Learning.  
The system recommends movies similar to a given movie by analyzing plot, genres, cast, and crew tags.

---

## 📌 Project Overview
- **Data Preprocessing:** Combined important features (overview, genres, keywords, cast, crew) into a single `tags` column.
- **Text Processing:**  
  - Tokenization  
  - Stemming using **NLTK PorterStemmer**  
  - Removed stop words  
- **Feature Extraction:** Transformed text into vectors using **CountVectorizer** (`max_features=5000, stop_words='english'`).
- **Similarity Measure:** Computed **cosine similarity** between movies to recommend the closest matches.
- **Recommendation:** Returns the top 5 similar movies for a given input.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **NLTK** (for stemming)
- **Scikit-learn** (CountVectorizer, cosine_similarity)
- **Jupyter Notebook**

### ✅ Recommended Movies:

-10th & Wolf
-Street Kings
-Sexy Beast
-Ladder 49
-Get Carter

📊 Results

-Successfully generates top 5 movie recommendations based on similarity.
-Handles NLP preprocessing (stemming + stopwords removal).
-Vector space of 5000 features ensures compact yet effective representation.
