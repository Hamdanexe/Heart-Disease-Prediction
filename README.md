## 2. Heart Disease Prediction

### Objective
Classify whether a person is at risk of heart disease based on their medical and demographic data.

### Dataset
- **File:** `heart_sample.csv` (sample of UCI Heart Disease Dataset)
- **Features:** Various clinical measurements (age, cholesterol, blood pressure, etc.)
- **Target:** `target` (1 = heart disease, 0 = no heart disease)

### Models Applied
- **Logistic Regression** for binary classification.
- Preprocessing:
  - Handling missing values (if any).
  - Scaling numeric features.

### Key Results & Findings
- Accuracy, ROC curve, and confusion matrix used for evaluation.
- Top influencing features: cholesterol level, age, and maximum heart rate achieved.
- Model showed good separation between positive and negative cases.
