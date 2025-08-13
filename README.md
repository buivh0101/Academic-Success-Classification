# Academic Success Classification

Classify academic success levels using machine learning models and feature engineering.

## Dataset
- **Train:** 76,518 rows × 38 columns (37 features, 1 target)
- **Features:** numerical predictors (int64, float64)
- **Target:** Academic success category

## Methods
- EDA and visualizations
- Preprocessing:
  - Handle missing values
  - Encode categorical variables
  - Scale features
- Models:
  - LogisticRegression
  - RandomForestClassifier
  - XGBClassifier
  - LGBMClassifier
  - CatBoostClassifier
  - GradientBoostingClassifier
  - SVC
  - KNeighborsClassifier
- Ensemble:
  - VotingClassifier for combined predictions
- Evaluation:
  - Accuracy, Precision, Recall, F1 score
