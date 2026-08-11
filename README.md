# AI-Based Manufacturing Digital Twin

An AI-based Digital Twin for manufacturing process monitoring,
quality prediction, energy optimization, closed-loop control,
fault detection, and automatic recovery.

## Project Overview

This project implements an AI-based manufacturing Digital Twin
using machine learning and data-driven process simulation.

## Main Capabilities

- Manufacturing process simulation
- AI-based product quality prediction
- AI-based energy consumption prediction
- Feature importance analysis
- Multi-objective quality-energy optimization
- Optimized operating-point recommendation
- Real-time process monitoring
- Closed-loop process control
- Manufacturing fault detection
- Automatic disturbance recovery
- KPI monitoring and visualization
- AI model and result export

## Machine Learning Models

Two Random Forest regression models are used:

1. Product Quality Prediction Model
2. Energy Consumption Prediction Model

### Input Parameters

- Temperature
- Pressure
- Machine Speed
- Material Ratio

## Model Performance

### Product Quality Model

- MAE: approximately 0.889
- R2 Score: approximately 0.689

### Energy Consumption Model

- MAE: approximately 1.293
- R2 Score: approximately 0.652

## Optimized Manufacturing Settings

- Temperature: approximately 439.138 C
- Pressure: approximately 4.227 bar
- Machine Speed: approximately 115.360
- Material Ratio: approximately 0.318
- Predicted Quality: approximately 95.159
- Predicted Energy Consumption: approximately 34.736

## Closed-Loop Control

The Digital Twin uses AI predictions and optimized targets
to automatically adjust manufacturing operating parameters.

Final closed-loop results:

- Initial Quality: 95.108
- Final Quality: 95.145
- Quality Improvement: approximately 0.037 points
- Initial Energy Consumption: 35.045
- Final Energy Consumption: 34.737
- Energy Reduction: approximately 0.307 units
- Energy Saving: approximately 0.88 percent

## Fault Detection and Automatic Recovery

A simulated manufacturing disturbance was introduced to
evaluate the fault-management capability of the Digital Twin.

After disturbance:

- Product Quality: approximately 91.236
- Energy Consumption: approximately 35.651

After automatic recovery:

- Product Quality: approximately 95.163
- Energy Consumption: approximately 34.734
- Quality Recovered: approximately 3.927 points
- Recovery Energy Reduction: approximately 0.917 units

The system reached the acceptable recovery region at
control cycle 14.

## Final System Status

SUCCESS

The Digital Twin successfully:

1. Detected the manufacturing disturbance
2. Evaluated its impact using AI models
3. Generated corrective operating parameters
4. Executed closed-loop recovery
5. Returned the manufacturing process to the optimized region

## Project Structure

digital-twin-manufacturing/

    notebooks/
        01_digital_twin_manufacturing.ipynb

    data/
        manufacturing_process_data.csv

    results/
        optimized_manufacturing_settings.csv
        closed_loop_control_history.csv
        fault_recovery_history.csv
        digital_twin_final_kpi_report.csv
        quality_prediction_model.pkl
        energy_prediction_model.pkl

    README.md
    requirements.txt

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Random Forest Regression
- Jupyter Notebook
- Joblib

## Applications

- Smart Manufacturing
- Industry 4.0
- AI-Based Manufacturing
- Intelligent Process Control
- Energy-Efficient Manufacturing
- Fault Detection and Recovery
- Industrial Decision Support Systems

## Disclaimer

The manufacturing dataset and disturbances used in this project
are synthetic and are intended for simulation, education,
and proof-of-concept development.
