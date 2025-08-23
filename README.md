# ai-ml-journey
Learning data science and AI from scratch
# AI/ML Learning Journey 🚀

Hi, I'm Azusa (Ahmed Faazil).  
I'm learning Data Science, AI, and Quantum Computing from scratch with the goal of doing research with MIT or Ivy League professors in 12th grade.  
This repo tracks my journey from total beginner to expert.

---

## 🧠 Day 5 Log – Titanic Dataset (Survival Rates)

- Grouped data by Sex, Pclass
- Learned how `.groupby()` + `.mean()` helps find trends
- Discovered: 
  - Women survived more than men
  - 1st Class passengers had higher survival
## 🧠 Day 6 Log – Rule-Based AI Prediction

- Built a function to predict Titanic survival based on sex, class, and age
- Achieved ~78% accuracy using manual rules
- Modified logic to explore better rules
- Understood the limitations of hardcoded rule-based models

## Day 7 – Machine Learning Begins: Decision Tree Classifier

- Trained my first ML model using `sklearn`
- Model accuracy: __74%__
- Learned how Decision Trees mimic rule-based logic automatically

## Day 8 – Random Forest Classifier

- Trained a Random Forest model on Titanic dataset
- Accuracy: __80%__
- Visualized feature importance
- Learned how multiple trees vote to reduce overfitting

## Day 9 – Model Evaluation & Cross-Validation

- Learned how to check model performance beyond just accuracy  
- Explored key metrics: **Precision, Recall, F1-score, Confusion Matrix**  
- Practiced evaluating a Decision Tree on the Iris dataset  
- Tried **Cross-Validation (5-fold)** to test stability of the model  
- Accuracy on Iris dataset: ~95% (varies with random split)  
- Understood why cross-validation is more reliable than a single train-test split

## Day 10 – First End-to-End ML Pipeline (Titanic)
- Built a clean **scikit-learn Pipeline** with `ColumnTransformer`
- Automatic **imputation**, **one-hot encoding**, and **scaling**
- Trained **Logistic Regression** + tried **Random Forest**
- Did a tiny **GridSearchCV** to tune
- Evaluated with **accuracy + classification report**
- **Saved the whole pipeline** (preprocess + model) as `titanic_pipeline_lr.joblib`


