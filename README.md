# Heart Failure Prediction and Analytics

### Team: Data Driven | Advanced Data Science | INFO 7390

## Project Overview
Heart failure, a debilitating condition, affects millions globally, compromising the heart's ability to pump blood efficiently. Our project utilizes supervised machine learning algorithms to predict heart disease risks, aiming to aid early detection and reduce mortality by providing accurate assessments of an individual's heart condition.

The models focus on identifying patients at risk of heart disease based on key health metrics, helping healthcare providers make informed decisions. 

## Objective
The goal of this project is to develop machine learning models that can accurately predict heart disease, thereby assisting in preventive healthcare strategies and reducing the global burden of heart failure.

## Dataset
The dataset used in this project includes key features related to heart disease risk, such as:

- **Age**: Age of the patient in years.
- **Sex**: Male or Female.
- **Chest Pain Type**: [Typical Angina (TA), Atypical Angina (ATA), Non-Anginal Pain (NAP), Asymptomatic (ASY)].
- **Resting Blood Pressure**: Measured in mm Hg.
- **Cholesterol**: Serum cholesterol in mg/dl.
- **Fasting Blood Sugar**: Binary feature indicating whether fasting blood sugar > 120 mg/dl.
- **Resting ECG**: [Normal, ST-T wave abnormality, Left ventricular hypertrophy].
- **Maximum Heart Rate Achieved**: Numeric value between 60 and 202.
- **Exercise Induced Angina**: [Yes, No].
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **ST Slope**: [Upsloping, Flat, Downsloping].
- **Heart Disease**: Target variable, where 1 indicates heart disease and 0 indicates normal.

## Machine Learning Algorithms
We employed multiple machine learning models to predict heart disease:

- Decision Tree
- Random Forest
- Multilayer Perceptron Classifier
- Support Vector Machine
- Extra Trees Classifier
- Logistic Regression
- K-Nearest Neighbors
- Gradient Boosting Classifier
- Stacking Classifier

## Best Performing Models
- **Random Forest**: 
  - Train Accuracy: 92.52%
  - Test Accuracy: 85.81%
  - F1 Score: 86.64%
  
- **Stacking Classifier**: 
  - Train Accuracy: 93.45%
  - Test Accuracy: 84.42%
  - F1 Score: 85.71%

## Conclusion
The Random Forest and Stacking Classifier models demonstrated the highest performance in heart disease prediction, making them ideal for early detection of heart failure risks. Future enhancements could include integrating advanced ECG analytics to further improve prediction accuracy.

## Scope for Future Work
We believe incorporating advanced ECG analytics could enhance the accuracy of our models. Additionally, further tuning of hyperparameters for the top models could lead to even better performance, potentially saving more lives by improving early detection and treatment strategies.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/hrishikeshwarrier4/Heart_Failure_Prediction.git
2. Run the jupyter notebook
   ```bash
   jupyter notebook HeartFailurePrediction&Analytics_TeamDataDriven_INFO7390_Summer23.ipynb


