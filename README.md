# Titanic Survival Prediction 🚢

**Data Science Internship Project 5**

## Project Overview
This project uses the famous Titanic dataset to predict which passengers survived the disaster based on features like age, sex, class, fare, family size, and title extracted from name.

The goal is to build a machine learning classification model using scikit-learn, evaluate it with proper metrics, and generate predictions for the test set.

## Skills Demonstrated
- Data cleaning and transformation
- Feature engineering (FamilySize, IsAlone, Title extraction)
- Exploratory Data Analysis (EDA)
- Model building with scikit-learn (Logistic Regression & Random Forest)
- Model evaluation (Accuracy, Precision, Recall, Confusion Matrix)
- Feature importance analysis
- Generating submission predictions

## Dataset
- **Train data**: 891 passengers with 'Survived' label
- **Test data**: 418 passengers (no 'Survived' label)
- Source: Kaggle Titanic Competition

## Results
- **Logistic Regression**: ~81% accuracy
- **Random Forest**: ~83-85% accuracy (best model used for final predictions)

Key Insights:
- Females had much higher survival rate
- 1st class passengers survived more than 3rd class
- Titles like "Mr" had low survival, "Miss/Mrs" higher
- Age, Fare, and Sex were among the most important features

## Files in Repository
- `Titanic_Survival_Prediction.ipynb` - Complete Jupyter notebook with code, EDA, models, and predictions
- `titanic_submission.csv` - Final predictions for test set (using Random Forest)
- `README.md` - This file

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Run all cells in order
3. The submission file will be generated and downloaded automatically in Colab

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Conclusion
This project demonstrates a complete end-to-end machine learning pipeline for a binary classification problem. Random Forest outperformed Logistic Regression and provided valuable feature insights.

Thank you for reviewing my work! 🚀

#DataScience #MachineLearning #Python #Titanic #Kaggle
