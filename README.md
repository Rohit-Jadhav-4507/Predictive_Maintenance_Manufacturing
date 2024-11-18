# Predictive_Maintenance_Manufacturing
This project uses machine learning for predictive maintenance in manufacturing, aiming to forecast machine failures and optimize schedules. Through Random Forest modeling and feature analysis, I identified key factors affecting equipment health, supporting proactive maintenance and reducing downtime.


# Objective
The goal of this project was to develop a predictive model to identify potential machine failures in a manufacturing setting. Predicting failures in advance allows maintenance teams to intervene proactively, minimizing downtime and optimizing repair schedules.


# Data Overview
- **Dataset**: Predictive Maintenance Dataset
- **Features**:
  - **Operational Parameters**: Air temperature, Process temperature, Rotational speed, Torque, Tool wear, etc.
  - **Failure Types**: 
      - **TWF** (Tool Wear Failure) 
      - **HDF** (Heat Dissipation Failure)
      - **PWF** (Power Failure)
      - **OSF** (Overstrain Failure)
      - **RNF** (Random Failures)
  - **Target Variable**: Machine failure (1 for failure, 0 for no failure)


# Model Development and Evaluation

- **Model**: Random Forest Classifier
- **Hyperparameter Tuning**: Performed using RandomizedSearchCV to optimize parameters for improved performance.
- **Performance Metrics**:
  - **Accuracy**: Achieved an accuracy of X% on the test set.
  - **Precision and Recall**: Balanced metrics for identifying machine failures accurately.
  - **ROC AUC Score**: An area under the ROC curve of X, indicating the model's ability to distinguish between failure and non-failure events.


# Key Findings

# Feature Importance
The top contributing features identified by the model were:
- **Heat Dissipation Failure (HDF)**: The most significant predictor of machine failure.
- **Overstrain Failure (OSF)** and **Power Failure (PWF)**: Also highly predictive, indicating a strong correlation with machine failure.
- **Torque [Nm]** and **Rotational speed [rpm]**: Operational parameters influencing machine performance and failure risk.

# Model Evaluation Results
- **ROC Curve**: The ROC curve showed a high true positive rate, indicating that the model effectively captures machine failures with minimal false positives.
- **Precision-Recall Curve**: High precision and recall indicate that the model balances identifying actual failures while minimizing false alarms.


# Interpretation of Results

# Feature Insights
- **HDF and OSF**: The high importance of HDF and OSF suggests that temperature management and strain control are crucial for machine longevity.
- **Torque and Rotational Speed**: Variations in these parameters may signal operational stress or wear on the equipment, leading to potential failures.

# Practical Implications
- **Proactive Maintenance**: By predicting failures in advance, maintenance teams can prioritize checks on machines showing high failure risk.
- **Cost Savings**: Early detection reduces unplanned downtime and allows for targeted maintenance, optimizing resources and reducing costs.


# Recommendations

1. **Operational Monitoring**:
   - Focus on monitoring parameters like heat dissipation, strain, and rotational speed, as these are key indicators of potential failures.

2. **Future Model Enhancements**:
   - Explore additional models (e.g., Gradient Boosting, XGBoost) to further enhance prediction accuracy.
   - Investigate interaction effects between operational parameters for deeper insights.

3. **Further Data Collection**:
   - Gathering more granular data on maintenance records and specific failure events may provide richer insights and improve model performance.

# Future Work
This project suggests additional areas for improvement, including the integration of more detailed maintenance logs, exploring advanced models, and analyzing operational parameter interactions.
