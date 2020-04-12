# Breast Cancer Detection

In this project I've used Breast Cancer Wisconsin (Diagnostic) Data Set from UCI machine learning repository to train different type of models in order to predict the likeliness of a person having breast cancer.

## Dataset information

Attribute Information: (class attribute has been moved to last column)
       Attribute                     Domain
   -- -----------------------------------------
   1. Sample code number            id number
   2. Clump Thickness               1 - 10
   3. Uniformity of Cell Size       1 - 10
   4. Uniformity of Cell Shape      1 - 10
   5. Marginal Adhesion             1 - 10
   6. Single Epithelial Cell Size   1 - 10
   7. Bare Nuclei                   1 - 10
   8. Bland Chromatin               1 - 10
   9. Normal Nucleoli               1 - 10
  10. Mitoses                       1 - 10
  11. Class:                        (2 for benign, 4 for malignant)

## Prediction Accuracy:

| Algorithm               | Test Accuracy |
| ----------------------- | ------------- |
| KNN                     | 0.9562        |
| Support Vector Machine  | 0.9635        |
| Random Forest           | 0.9489        |
| XGBoost                 | 0.9562        |