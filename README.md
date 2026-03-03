# Sensor Performance Analytics | Industrial IoT & KPI Monitoring

In this project, I built a monitoring framework for CNC manufacturing equipment using multi-sensor industrial data. The goal was to move beyond simple anomaly detection and create a health scoring system that highlights degradation trends before failure occurs.

The final model integrates vibration behavior, temperature drift, and alert concentration into a single Machine Health Index (0–100). By incorporating vibration velocity (rate of change), the model became more sensitive to rapid degradation patterns.

As a result, the system detected a performance decline approximately 3 hours before the recorded critical failure event.

  ![Industrial Sensor Anomaly Detection](images/sensor_anomaly_detection.png)

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
