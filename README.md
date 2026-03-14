# Machine Learning Projects

This repository showcases my Machine Learning projects using tools such as 
NumPy, Pandas and PyTorch. I link my projects to my real world passion for 
motorsports by creating relevant tools that can be used in racing teams.

---

## 01 — NumPy

### Battery Sensor Data Analyser
A NumPy-based data processing pipeline for cleaning and analysing EV battery 
sensor data, inspired by real BMS work on a Formula Student electric vehicle.

**What it does**
- Simulates realistic voltage, current and temperature sensor readings
- Injects real-world faults (overvoltage, overcurrent, thermal spikes)
- Detects and removes physically impossible readings using domain-based thresholds
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

**Stack:** Python · NumPy · Matplotlib

**How to run**
1. Clone the repo
2. Install dependencies: `pip install numpy matplotlib`
3. Open the notebook in VS Code or Jupyter
4. Run All cells

📓 [View Notebook](01-numpy/Battery%20Sensor%20Data%20Analyser.ipynb)

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
