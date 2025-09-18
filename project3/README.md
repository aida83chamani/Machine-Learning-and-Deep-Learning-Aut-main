# Project 3 — Medical Transcript Classification with Bag-of-Words  

**Notebook:** `Aida Chamani_Project3.ipynb`  
**Folder:** `Project 3`  

---

## 📌 Project Description  
This project explores **text classification of medical transcripts** using **Bag-of-Words (BoW)** feature extraction with two representations:  
1. **Binary BoW** (presence/absence of terms)  
2. **Frequency BoW** (term counts)  

Several **machine learning classifiers** are trained and evaluated comparatively to identify the most effective approach for this task.  

---

## 📊 Dataset  
- **Source:** Provided CSV files (`train.csv`, `valid.csv`, `test.csv`)  
- **Content:** Medical transcripts (text) with associated labels  
- **Splits:** Training, validation, and testing sets  

---

## 🛠️ Tools & Libraries  
- Python 3.x  
- NumPy, Pandas  
- scikit-learn (Logistic Regression, Decision Trees, Random Forests, metrics)  
- XGBoost (`XGBClassifier`)  
- tqdm (progress bars)  

---

## 🚀 Workflow  
1. **Preprocessing:** Cleaning text (regex, punctuation removal, tokenization)  
2. **Feature Extraction:**  
   - Binary Bag-of-Words  
   - Frequency Bag-of-Words  
3. **Model Training:** Logistic Regression, Decision Tree, Random Forest, XGBoost  
4. **Evaluation:** Models compared using **F1-score** on validation and test sets  
5. **Analysis:** Study impact of BoW type on classification performance  

---

## 📈 Results  
- **Binary vs. Frequency BoW:** Performance varies depending on classifier.  
- **Logistic Regression** performs strongly on sparse binary features.  
- **XGBoost** benefits from frequency-based representations.  
- **F1-score** provides balanced evaluation, especially useful for imbalanced classes.  

---

## 🎯 Learning Outcome  
Through this project, we gain experience with:  
- Applying Bag-of-Words representations for text classification  
- Comparing ensemble and baseline classifiers on medical data  
- Evaluating models using F1-score for imbalanced classification problems  
- Understanding trade-offs between binary and frequency BoW features  
