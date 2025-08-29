# Flipkart Review Sentiment Analysis  

## 📌 Overview  
This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify Flipkart product reviews as **positive** or **negative** based on user ratings and review text.  

---

## 📊 Dataset  
- **Source:** `flipkart_data.csv`  
- **Columns:**  
  - `review`: The customer review text.  
  - `rating`: Rating given by the customer.  
- **Labels:**  
  - Positive (1): rating ≥ 5  
  - Negative (0): rating < 5  

---

## 🔧 Features of the Pipeline  
1. **Data Cleaning & Preprocessing**  
   - Remove punctuation, lowercase conversion, tokenization, and stopword removal.  
2. **Feature Engineering**  
   - TF-IDF vectorization (2500 features).  
3. **Visualization**  
   - Word cloud for frequent words in positive reviews.  
   - Distribution plots for ratings.  
4. **Modeling**  
   - Decision Tree Classifier.  
   - Performance evaluated with accuracy and confusion matrix.  

---

## ⚙️ Installation  
Clone this repository and install dependencies:  
```bash
git clone <repo_url>
cd sentiment-analysis
pip install -r requirements.txt
