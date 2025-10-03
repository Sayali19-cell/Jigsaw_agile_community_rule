# Jigsaw_agile_community_rule
"Baseline model for Jigsaw Reddit Rule Violation Detection using TF-IDF and Logistic Regression."


# Jigsaw Reddit Rule Violation Detection

This project implements a baseline machine learning model for the **Jigsaw "Reddit Rule Violation Detection"** task. The goal is to classify whether a Reddit comment violates subreddit rules such as "No Advertising" or "No Legal Advice".

## 📂 Project Structure
- `train.csv` → Training dataset with labeled comments.  
- `test.csv` → Test dataset without labels.  
- `notebook.ipynb` → End-to-end workflow (loading data, preprocessing, training, prediction).  
- `test_with_predictions.csv` → Final submission file with predictions.  

## ⚙️ Approach
1. Preprocess the `body` text using **TF-IDF vectorization**.  
2. Train a **Logistic Regression** classifier as a baseline model.  
3. Generate predictions for the test dataset.  
4. Save results in the required Kaggle submission format.  

## 📊 Output Format
The final CSV (`test_with_predictions.csv`) contains:
- `row_id` → unique identifier from test set  
- `predicted_rule_violation` → 0 (No violation) or 1 (Violation)  

## 🚀 Future Improvements
- Experiment with advanced NLP models (BERT, RoBERTa).  
- Explore multi-task learning with rule + subreddit metadata.  
- Use ensemble methods for better generalization.  

---

### 🔗 Reference
This project is based on the **Jigsaw - Comment Rule Classification (Reddit)** dataset and competition format.
