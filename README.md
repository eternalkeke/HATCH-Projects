# Gait Analysis Notebooks

This repository contains three Jupyter notebooks developed during my internship at NUS iHealthtech (HATCH group). These tools were built to support research involving an IMU-embedded insole.

---

## Notebooks

### 1. `gait_parameter_workbook.ipynb`

An interactive notebook for exploring gait data from individual trials.

Features:
- Load and combine raw IMU data files
- Filter and preprocess time-series data
- Calculate basic gait parameters and compare against a reference system

Designed for small-scale analysis and manual inspection of trials.

### 2. `gait_parameter_sweep.ipynb`

This notebook performs parameter tuning across two parameters of the algorithm. 

Features:
- Load and process multiple recording files
- Sweep through two key parameters
- Analyze and visualize results to determine ideal values

Used to improve the accuracy of stride length and stride width calculations.
Sample output [Parasweep_results.png]


### 3. `gait_report_pdf_extractor.ipynb`

Parses gait reports in PDF format exported from the Awinda MotionCloud platform and converts them into structured CSV format.

Features:
- Extracts text-based gait parameters
- Converts data into a pandas DataFrame for further processing

Useful for digitizing and analyzing summary reports.

---

## Dependencies

These notebooks require the following Python packages, available through pip install:

- pandas  
- numpy  
- plotly  
- ipywidgets  
- matplotlib  
- seaborn  
- glob  
- re  
- camelot  

---

## Author

Yang Kaiji
