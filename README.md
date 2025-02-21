# Titanic Dataset Analysis - README 

## Overview 
This project analyzes the Titanic dataset to explore patterns in passenger survival and build a predictive model. The dataset includes information such as passenger age, class, fare, and survival status. 

## Dataset 
The Titanic dataset contains the following key features: 
- **Survived**: 0 = No, 1 = Yes (Target variable) 
- **Pclass**: Ticket class (1st, 2nd, 3rd) 
- **Name**: Passenger name 
- **Sex**: Male or Female 
- **Age**: Passenger's age 
- **SibSp**: Number of siblings/spouses aboard 
- **Parch**: Number of parents/children aboard 
- **Ticket**: Ticket number 
- **Fare**: Passenger fare 
- **Cabin**: Cabin number 
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) 


## Project Structure 

1. **Data Exploration** 
- Load dataset 
- Understand data structure (columns, missing values, types) 
- Summary statistics 

2. **Data Cleaning & Wrangling** 
- Handling missing values (e.g., filling missing ages using median values) 
- Encoding categorical variables (e.g., converting 'Sex' and 'Embarked' into numerical values) 

3. **Exploratory Data Analysis (EDA)** 
- Visualizations of survival rates by different features 
- Correlation analysis 

4. **Feature Engineering** 
- Creating new features (e.g., family size, title extraction from names) 

5. **Modeling** 
- Splitting data into training and test sets 
- Applying machine learning models (e.g., Logistic Regression, Random Forest) 
- Evaluating model performance using accuracy, precision, recall, and F1-score 

6. **Model Testing & Insights** 
- Testing the model on unseen data 
- Extracting key insights and factors influencing survival ## Requirements To run the analysis, install the following dependencies: ``` pip install pandas numpy seaborn matplotlib scikit-learn ``` 

## Running the Project 
Run the Jupyter Notebook or Python script to execute the analysis step-by-step: ```python main.py ``` 

## Conclusion 
This project provides insights into passenger survival on the Titanic and applies machine learning models to predict outcomes. Key takeaways include the impact of gender, class, and fare on survival probability. 

## Credits Dataset source: (https://github.com/datasciencedojo/datasets/blob/master/titanic.csv) 