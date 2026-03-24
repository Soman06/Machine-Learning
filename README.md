# Machine Learning Projects

This repository showcases my Machine Learning projects using tools such as 
NumPy, Pandas and PyTorch. I link my projects to my real world passion for 
motorsports by creating relevant tools that can be used in racing teams.

---

## 01 — NumPy

### Battery Sensor Data Analyser
A NumPy-based data processing pipeline for cleaning and analysing real Li-ion 
battery discharge data from the NASA Ames Prognostics Center of Excellence. 
Inspired by BMS work on a Formula Student electric vehicle.

![Sensor Analysis](01-numpy/sensor_analysis.png)

**What it does**
- Loads real Li-ion battery discharge data from the NASA Ames 
  Prognostics Center of Excellence (Battery 00005 dataset)
- Applies domain-based physical limits to filter invalid readings
- Normalises data across sensors using Z-score standardisation
- Identifies the most anomalous readings using a composite anomaly score
- Visualises cleaned sensor traces with mean baseline

**Concepts demonstrated**
- Boolean masking for outlier removal
- Broadcasting and axis-based normalisation
- Vectorised operations (no loops over data)
- argsort-based anomaly ranking
- Z-score standardisation

**Background**
During my Formula Student work I debugged electrical faults in a real EV 
powertrain. This project applies the same fault-detection logic 
programmatically using NumPy.

**Stack:** Python · NumPy · Pandas · Matplotlib

**How to run**
1. Clone the repo
2. Install dependencies: `pip install numpy matplotlib pandas openpyxl`
3. Open the notebook in VS Code or Jupyter
4. Run All cells

📓 [View Notebook](01-numpy/Battery%20Sensor%20Data%20Analyser.ipynb)
**Data:** [NASA Li-ion Battery Aging Dataset](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset)

---

## 02 — Pandas

### EV Lap Data Analyser
*(in progress)*

---

## 03 — Scikit-learn
*Coming soon*

---

## 04 — PyTorch
*Coming soon*
