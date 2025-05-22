# Gait Analysis Notebooks

This repository includes three Jupyter notebooks created during my internship at NUS iHealthtech (HATCH group) to support research on an IMU-embedded insole. The notebooks demonstrate the data processing and analysis pipeline; however, the actual data files are not included due to sensitivity.

---

## Notebooks

### 1. `gait_data_analysis_workbook.ipynb`

An interactive notebook for exploring gait data from individual trials.

Features:
- Load and combine raw IMU data files
- Filter and preprocess time-series data
- Calculate basic gait parameters and compare against a reference system
- Display a interactive scatter plot and Bland Altman plot on the trial data

Designed for small-scale analysis and manual inspection of trials.
Sample output [`images\Data_analysis_result.png`]

### 2. `gait_parameter_sweep.ipynb`

This notebook performs parameter tuning across two parameters of the algorithm. 

Features:
- Load and process multiple recording files
- Sweep through two key parameters
- Analyze and visualize results to determine ideal values

Used to improve the accuracy of stride length and stride width calculations.
Sample output [`images\Parasweep_results.png`]


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
