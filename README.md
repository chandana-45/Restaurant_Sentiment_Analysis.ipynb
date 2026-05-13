# Restaurant Review Sentiment Analysis

## Project Overview
This project performs sentiment analysis on restaurant reviews using machine learning techniques. The goal is to classify reviews as positive or negative based on their content.

---

## Steps Performed

### Step 1: Data Loading
Loaded the dataset containing restaurant reviews and sentiment labels.

### Step 2: Exploratory Data Analysis (EDA)
- Checked dataset structure  
- Analyzed class distribution  
- Identified missing values  

### Step 3: Data Preprocessing
- Removed special characters and noise  
- Converted text to lowercase  
- Removed stopwords while preserving negation words (not, no)  
- Applied stemming  

### Step 4: Feature Extraction
- Used TF-IDF and CountVectorizer  
- Implemented bi-grams (n-grams) for better context understanding  

### Step 5: Model Training
Trained multiple models:
- Logistic Regression  
- Naive Bayes  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  

### Step 6: Model Evaluation
- Accuracy score  
- Confusion matrix  
- Classification report  

### Step 7: Hyperparameter Tuning
- Used GridSearchCV to optimize model performance  

### Step 8: Final Model
- Selected the best-performing model based on accuracy and evaluation metrics  

---

## Results
- Achieved approximately 81% accuracy  
- The model successfully classifies restaurant reviews into positive and negative sentiments  

---

## Key Insights
- Preserving negation words improves sentiment detection  
- Bi-grams help capture contextual meaning  
- Naive Bayes and SVM perform well for text classification tasks  

---

## Conclusion
- Built a complete end-to-end NLP pipeline  
- Improved model performance through preprocessing and tuning  
- Developed a reliable sentiment classification system  

---

## Technologies Used
- Python  
- Scikit-learn  
- NLTK  
- Google Colab  

---

## Author
Your Name
