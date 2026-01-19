Name-Swastik
Roll No-102316020
================================================================================
CREDIT CARD FRAUD DETECTION - SAMPLING ANALYSIS REPORT
Thapar University
================================================================================

DATASET INFORMATION:
--------------------------------------------------------------------------------
Dataset: Credit Card Fraud Detection
Original Shape: (772, 31)
Balanced Shape: (1526, 30)
Sample Size (per technique): 384

SAMPLING TECHNIQUES USED:
--------------------------------------------------------------------------------
1. Simple Random Sampling
2. Systematic Sampling
3. Stratified Sampling
4. Cluster Sampling (K-Means)
5. Bootstrap Sampling

MACHINE LEARNING MODELS USED:
--------------------------------------------------------------------------------
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. XGBoost

RESULTS TABLE (Accuracy %):
--------------------------------------------------------------------------------
                           Sampling1   Sampling2   Sampling3   Sampling4   Sampling5
M1 - Logistic Regression   97.402597   84.415584   94.805195   88.333333   93.506494
M2 - Decision Tree         98.701299   93.506494  100.000000   96.666667   96.103896
M3 - Random Forest        100.000000  100.000000  100.000000  100.000000  100.000000
M4 - SVM                   66.233766   70.129870   75.324675   71.666667   76.623377
M5 - XGBoost               98.701299   98.701299   98.701299  100.000000   96.103896

BEST COMBINATIONS:
--------------------------------------------------------------------------------
Overall Best: M3 - Random Forest with Sampling1
Highest Accuracy: 100.00%

AVERAGE PERFORMANCE BY MODEL:
--------------------------------------------------------------------------------
M3 - Random Forest          100.00
M5 - XGBoost                 98.44
M2 - Decision Tree           97.00
M1 - Logistic Regression     91.69
M4 - SVM                     72.00

AVERAGE PERFORMANCE BY SAMPLING:
--------------------------------------------------------------------------------
Sampling3    93.77
Sampling5    92.47
Sampling1    92.21
Sampling4    91.33
Sampling2    89.35

CONCLUSION:
--------------------------------------------------------------------------------
This analysis demonstrates that sampling technique selection significantly
impacts model performance. The best model-sampling combination achieved
100.00% accuracy. Tree-based ensemble methods showed robust
performance across different sampling techniques.
