# Simulated Event Logs and Context-aware Analysis

This repository contains the supplementary materials for **Chapter 6** of the thesis *Integrating IoT Data into Business Process Event Logs for Context-aware Analytics*.

## Repository Structure
- **1. Initialisation & Process Data**
  - `object_initialiser_iot/` – Object initialisation scripts/data  
  - `truck_bp_iot_v4/` – Truck business process v4 data/scripts  

- **2. Raw & Processed IoT Data**
  - `Random_data_generation.ipynb` – Generate synthetic IoT data  
  -  `empty_weight_history.csv` – Historical empty truck weights  
  - `hourly_rainfall_data.csv` – Hourly rainfall dataset  
  - `infrared_sensors_interdependency.csv` – Infrared sensor dependency data  
  - `weight_sensor_data.csv` – Weight sensor readings  
  - `Silo_iot_data_with_dewpoint_prob.csv`  
  - `Reshaped_Silo_IoT_Data.csv`  
  - `Reshaped_Silo_IoT_Data_with_dewpoint_prob.csv`  
  - `Silo_iot_date.csv`  

- **3. Event Logs & Object Tables**
  - `CargoPickup_IoT.sqlite` – Main SQLite database  
  - `event_*.csv` – Event log CSV files (per activity)  
  - `object_*.csv` – Object table CSV files (per object type)
  - `object_IoTobject.csv`- object and IoT object relations table
  - `object_object.csv`- object and object relations table
  - `event_IoTobject.csv`- event and IoT object relations table
  - `event_object.csv`- event and object relations table
  - `TruckGPSRecord.csv` – Truck GPS tracking data  
  - `InfraredSensorRecord.csv` – Infrared sensor readings  
  - `TruckHistoryWeightRecord.csv` – Truck weight history  

- **4. Log Processing and Analysis Notebooks**
  - `scenario_based_analysis.ipynb` – Scenario-based analysis  
  - `turnaround_analysis.ipynb` – Turnaround time analysis  
  - `truckRouteAnalysis.ipynb` – GPS route analysis    
  - `CSVs_to_OCEL_SQLITE.ipynb` – Convert CSVs to OCEL SQLite  

- **5. Visualisations (PNG)**
  - `bad_pickups_*.png` – Failed pickup visualisations  
  - `process_stage_unauthorised_trucks.png` – Unauthorised trucks by stage  
  - `failedWeight_path.png`  
  - `weighbridge_utilisation.png`  
  - `Distribution_Successful_Pickups.png`  
  - `rain_turnaround_comparison.png`  
  - `Normal_Long_Path_Duration.png`  
  - `Normal_Long_Unauthorised_Distribution.png`  
  - `detour_ratio_all_paths.png`  
  - `Distribution_of_durations_between_consecutive_events.png`  

- **6. CPN Models for simulation**
  - `truck_bp_iot_final_updated_final.cpn` – Coloured Petri Net model
 
- **7. Section 6.3 analyses**
  - `Ch6.3_Analysis.ipynb` – KPI-oriented analysis notebook  
  - `Ch6.3_Analysis2.ipynb` – Object-centric analysis notebook  
  - `Dirigo.sqlite` – SQLite database for analysis
