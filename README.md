## Predictive Maintenance for Manufacturing ##

# Objective
 The goal of this project is to develop a predictive model to identify potential machine failures in a manufacturing setting. Predicting failures in advance allows 
 maintenance teams to intervene proactively, minimizing downtime and optimizing repair schedules.

# Data and Features

- Dataset: Predictive Maintenance Dataset
- Features: Operational parameters (air temperature, process temperature, rotational speed, torque, tool wear) and various failure types (Tool Wear, Heat 
            Dissipation, Power, Overstrain, Random)
- Target: Machine failure status (1 for failure, 0 for no failure)

# Model
- Model Used: Random Forest Classifier
- Evaluation Metrics: ROC-AUC, Precision-Recall, and accuracy

# Key Findings
- High feature importance for parameters such as Heat Dissipation and Overstrain Failure
- Model demonstrates strong ability to forecast failures with minimal false alarms
  Recommendations

# Proactive maintenance scheduling based on high-risk machines
- Further data collection and alternative model exploration for improved accuracy

# Future Work
- This project suggests additional areas for improvement, including the integration of more detailed maintenance logs, exploring advanced models, and analyzing 
  operational parameter interactions.

