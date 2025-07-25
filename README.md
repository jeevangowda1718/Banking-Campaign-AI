A machine learning project that analyzes and predicts the success of bank marketing campaigns using the Bank Marketing dataset. The model helps identify which customers are more likely to subscribe to a term deposit based on various demographic and campaign-related features.

## 🔍 Overview

This project uses data analysis and supervised machine learning techniques to:

- Understand customer behavior
- Visualize key patterns and trends
- Build predictive models to identify potential subscribers

The dataset comes from direct marketing campaigns of a Portuguese banking institution.

## 📊 Dataset

The dataset is publicly available from the UCI Machine Learning Repository and includes information such as:

- Age, job, marital status, education, balance, etc.
- Contact communication type
- Last contact duration
- Previous marketing outcomes
- Target variable: `y` (whether the client subscribed to a term deposit)

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Modeling:** Logistic Regression, Random Forest, Decision Tree
- **Notebook:** Jupyter Notebook

## 🧠 ML Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Distribution of key variables
   - Correlation matrix
   - Visualization of campaign success rate

3. **Model Training & Evaluation**
   - Train-test split
   - Model fitting
   - Accuracy, Precision, Recall, F1-Score
   - Confusion matrix

4. **Prediction & Conclusion**
   - Predict potential term deposit subscribers
   - Summarize insights

## 📈 Results

- Achieved promising accuracy and precision on test data
- Identified key features that influence client subscription
- Potential for integration into marketing automation systems

## 📁 File Structure

BankPromoPredictor/
├── Bank Marketing.ipynb # Main Jupyter notebook
├── README.md # Project description
├── bank.csv # Bank Marketing dataset (if included)
