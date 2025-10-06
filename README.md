#  Predicting Titanic Survival with automated Machine Learning

This project utilizes the Titanic dataset to predict the passenger survival. Cross-validation and Hyperparameter tuning are used to select the best-performing model and its parameters.

## 🔍 Project Overview:

✅ Data cleaning, feature engineering, and encoding
✅ Compares 5 different algorithms with proper scaling
✅ Uses GridSearchCV for hyperparameter tuning with cross-validation
✅ Evaluates on held-out test data to prevent overfitting
✅ Ranks models by performance and provides detailed analysis

## 🛠 Technical Implementation:

• **Data Preprocessing**: Handling missing values, feature encoding, scaling
• **Model Comparison**: Random Forest, SVM, Logistic Regression, Naive Bayes, Decision Trees
• **Hyperparameter Tuning**: GridSearchCV with 5-fold cross-validation
• **Evaluation**: Test set performance, feature importance, training time analysis

## 📈 Key Results:

🏆 **Random Forest** emerged as the best model with **82%** accuracy
⚡ **Naive Models** were the fastest to train
📊 Top Features: Passenger class, gender, and fare

## 💡Insights:

• First-class passengers had significantly higher survival rates
• Gender was the strongest predictor of survival


