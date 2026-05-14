# Machine-Learning-Project

Trained 3 machine learning models- LogisticsRegression, RandomForestClassifier and XGBClassifier on a real Lending Club Dataset.The main objective of the project was to  predict whether a loan will be fully paid or will default. Basically, I tried to build a loan risk predicting system.

The Dataset has 42,538 rows and 18 columns. Columns include information about loan amount, annual income, interest rate, credit history, loan status among other. "Loan_status" is my prediction target. I removed unnecessary columns and kept the rest as features. 
I balanced the dataset after cleaning, split it into train and test and trained the models as mentioned above. Then I evaluated the results. The metric used was AUC. And formed a comparison table. 

<img width="400" height="150" alt="Screenshot 2026-05-14 180058" src="https://github.com/user-attachments/assets/61ccc079-5585-40c4-a9f1-f5d2570c1fbc" />

**Conclusion** : According to AUC metric comparison, LogisticsReression model gave the best results among others used, with 0.50 as AUC score. 

