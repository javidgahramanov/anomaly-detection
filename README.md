# anomaly-detection

Anomaly Detection in Kitchen Appliance Usage
This repository contains the implementation and experimental results for detecting anomalies in domestic energy consumption using machine learning. The project focuses on identifying abnormal usage patterns in major household appliances – dishwasher (DISHWASH), home heating (HEATHOME), and air conditioning (AIRCOND) – by leveraging the Isolation Forest algorithm.

**Overview**

Domestic energy consumption data often contain subtle irregularities that may indicate energy loss, appliance malfunction, or atypical user behavior. This project presents an unsupervised approach using the Isolation Forest (IF) method to detect such anomalies. The methodology involves:

Data Preprocessing: Normalization of high-resolution (1Hz) appliance power measurements.
Feature Selection: Focusing on three primary features (DISHWASH, HEATHOME, AIRCOND) that contribute significantly to overall energy usage.
Anomaly Detection: Employing Isolation Forest to separate outliers through recursive partitioning, with further validation using Kernel Density Estimation (KDE) analysis.
Visualization: Utilizing pair plots, 3D visualizations, and anomaly score histograms to verify and interpret the detection results.
Key Features
Unsupervised Learning: Uses Isolation Forest to efficiently and scalably detect anomalies without the need for labeled data.
Bimodal Distribution Analysis: KDE plots indicate bimodal distributions in the selected features, highlighting distinct usage patterns.
Interactive Visualizations: Provides pair plots and histograms to clearly demonstrate the isolation of outlier data points.
Practical Applications: Supports smart home monitoring systems, predictive maintenance, and energy optimization.



![image](https://github.com/user-attachments/assets/70bd5fa6-771e-472f-801e-bfd6488d117b)

![image](https://github.com/user-attachments/assets/344e9ca4-7a0d-4702-ac0f-71bee6da8eb9)


![image](https://github.com/user-attachments/assets/b551483b-90c3-496d-84d2-3f39d223164e)

KDE method

![image](https://github.com/user-attachments/assets/1d96972f-9f9d-4477-b8df-5ee3cab9cae3)
Pairt plot for anmoly detection using isolation forest
