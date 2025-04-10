# Project Overview - Water Sensor Data Trends - 2014

This interactive Tableau dashboard visualizes key trends and anomalies from a SCADA-based water sensor system. The goal is to provide actionable insights into operational performance, water flow, and equipment behavior to support preventative maintenance and improve system reliability.
The dashboard simulates how a utility operator or engineer might monitor sensor data in real-time to identify irregularities—such as pressure drops, flow fluctuations, or out-of-range readings—that could indicate equipment wear, leaks, or efficiency issues.

## Data Sources

For this project, I used the **BATADAL: Cyber Attacks Detection in Water Systems** dataset available on Kaggle:  
🔗 [View Dataset on Kaggle](https://www.kaggle.com/datasets/minhbtnguyen/batadal-a-dataset-for-cyber-attack-detection)

Although the dataset was originally designed for cyberattack detection in water distribution systems, I used it to practice building a Tableau dashboard that summarizes normal SCADA sensor data over one year.

To align with this goal, I used only the `training_dataset_1.csv` file, which represents one year of normal operations without simulated attacks.

This file contains real-time SCADA measurements from a simulated city water network, including:

- **Tank water levels** (`L_T#`)  
- **Pump and valve status** (`S_PU#`, `S_V#`)  
- **Flow rates** (`F_PU#`, `F_V#`)  
- **Inlet and outlet pressures** (`P_J#`)  

These variables represent standard telemetry used in municipal water systems and were ideal for developing a sensor monitoring dashboard.

## Data Preparation and Transformation 



