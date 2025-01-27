# Anamoly-detection-in-finanancial-transaction
This project implements an anomaly detection system for financial transactions using Isolation Forest. The dataset includes transaction-related features such as transaction amounts, frequency, and user demographics to identify unusual or potentially fraudulent activity.

**Features of the Code**
Data Preprocessing:

Handles missing values.
Encodes categorical variables (e.g., Gender and Account_Type).
Normalizes numerical features to ensure consistency.
Anomaly Detection:

Uses Isolation Forest, an unsupervised learning algorithm, to detect anomalies.
Flags anomalies based on a specified contamination ratio (default: 5%).
Outputs:

Adds a new column Anomaly, with labels:
"Anomaly": Records identified as anomalies.
"Not Anomaly": Normal records.
Saves the results to a CSV file named anomaly_detection_with_labels.csv.
Customizable:

You can modify the contamination parameter and other settings in the Isolation Forest to adjust sensitivity.
**Requirements**
The following Python libraries are required to run the code:

pandas
numpy
scikit-learn
matplotlib
seaborn
