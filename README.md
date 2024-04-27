Heart Attack Prediction
This project uses machine learning ensemble techniques to predict the likelihood of a heart attack based on various features and parameters.

Overview
Ensemble Method: Utilizes an ensemble of decision tree estimators, specifically [20, 40] estimators, where using 20 yielded better generalization error.
Depth Constraint: The decision trees are constrained to a maximum depth of 4, with the bootstrap parameter set to True to enable random sampling with replacement.
Data Considerations: Acknowledges that the limited dataset used may not generalize well broadly, as alternative datasets were not identified.
User Interface: Utilizes Gradio for a user-friendly interface to interact with the model predictions.
Performance Metrics
Recall: Achieves a recall of approximately 0.98, indicating the model's ability to correctly identify positive cases (heart attacks).
Average Accuracy: Demonstrates an average accuracy of approximately 0.98 across predictions.

