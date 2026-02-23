# Sensor Performance Analytics | Industrial IoT & KPI Monitoring

## Project Overview
This project focuses on analyzing multi-modal industrial operational datasets to monitor machine performance, identify degradation patterns, and detect anomalies. Using data from a CNC manufacturing environment, I developed a synchronized analytical engine and a multi-tier anomaly detection system to support predictive maintenance.

## Key Achievements
- **Multi-Sensor Integration:** Combined 6 industrial data streams (Vibration, Temperature, Pressure, Humidity, PLC Logs, Machine Status) into a unified Master DataFrame.
- **KPI Engineering:**
  1. Machine Availability: 95.83%
  2. Rolling statistics to reduce noise and reveal degradation trends.
- **Anomaly Detection:** 
  - Implemented Z-Score logic with dual thresholds (Warning >2, Critical >3).  
  - Flagged performance drift 30 minutes before documented failures.

## Repository Structure
- `notebooks/` – Python analysis (EDA, KPI engineering, anomaly detection)  
- `data/`  
  - `raw/` – Original industrial sensor dataset  
  - `processed/` – Engineered dataset (`processed_sensor_data.csv`)  
- `powerbi/` – Dashboard files  
- `images/` – Visualizations  

## Data Attribution
- **raw/** dataset provided by Santosh Kumar (IEEE DataPort)  
- **processed/** dataset, analytical logic, KPI definitions, and anomaly detection framework are my original work.

## Tech Stack
- Python (Pandas, NumPy, Matplotlib)  
- Power BI  
- Time-Series Analysis | Statistical Outlier Detection | Feature Engineering  

## Author
**Soheyla Moghadam**  
Data Analyst | Industrial IoT
