# Heart disease detection

## 📌 Project Overview

This machine learning project aims to detect heart disease. The dataset is preprocessed, visualized, and cleaned, and then used to train a classification model that predicts whether a person having a heart disease or not.

## ✅ Steps Performed

1. **Data Collection**  
   Loaded the dataset (`eheart-disease - heart-disease.csv`) containing heart features and labels.

2. **Data Cleaning**  
   - Checked for null values  
   - Handled outliers using the IQR method  

3. **Data Visualization**  
   - Used box plots,bar graphs and histograms to explore distributions  

4. **Data Preprocessing**   
   - Split the dataset into training and testing sets

5. **Model Selection & Training**  
   - Used **Logistic Regression** with max_iter=1000`  
   - Evaluated the model with classification metrics and a confusion matrix

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
