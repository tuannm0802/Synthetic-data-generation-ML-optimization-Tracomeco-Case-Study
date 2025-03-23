# Synthetic-data-generation-ML-optimization-Tracomeco-Case-Study

The code files are separate into 2 main part:

1. Data generation, preprocessing
   
(Here by using preprocessing methods, we evaluate 3 preprocessing scenarios to ensure the models working properly, and to testify the synthetic data quality through every each adding methods)

- Scenario 1
  
      - Training: Synthetic data balanced by SMOTE
  
      - Testing: Using Synthetic data & Real data (balanced by SMOTE & Raw)
- Scenario 2
  
      - Training: Synthetic data with additional features (COVID-19 related timeline converted to interger format + balanced by SMOTE)
  
      - Testing: Using Synthetic data & Real data (balanced by SMOTE) + raw data
- Scenario 3
  
      - Training: Synthetic data with feature selection between Synthetic and Real data (Mutual Information Score + Scenario 2' methods)
  
      - Testing: Using Synthetic data & Real data (balanced by SMOTE) + raw data
      
2. Machine Learning Optimization

- Optimization 5 models (RF, DT, XGB, LGBM, LR)
   
