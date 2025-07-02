![image](https://github.com/user-attachments/assets/fe0a9182-0199-41b7-97d3-1878ad71d12b)


# MScIS Thesis: Optimizing Data Quality in Real-Time, Time Series ETL Pipelines Using Monte Carlo Methods and Machine Learning

📘 A research project submitted in partial fulfillment of the requirements for the degree of Master of Science in Information Systems at Uganda Martyrs University (UMU), Nkozi.

## 🧠 Abstract

This research presents a hybrid framework that integrates **Monte Carlo Markov Chain (MCMC)** methods and **Machine Learning (ML)** to improve data quality in **real-time, time series ETL pipelines**. The system is evaluated using simulated sensor streams with injected anomalies and visualized via Grafana dashboards.

## 🎯 Objectives

- Develop an MCMC-based simulator to inject and correct anomalies.
- Integrate machine learning models to learn and adapt from historical errors.
- Prototype a real-time ETL pipeline with Python, NiFi, InfluxDB, and Grafana.
- Evaluate performance using time series anomaly detection metrics.

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, PyMC3, TensorFlow)
- **Apache NiFi** for data flow automation
- **InfluxDB** for time series storage
- **Grafana** for real-time visualization
- **Docker** for containerized deployment
- **LaTeX** for documentation and presentation (Beamer)

## 📁 Repository Structure

```bash
├── data/                   # Raw and simulated datasets
├── notebooks/              # Jupyter notebooks for exploration
├── scripts/                # Python scripts for simulation, MCMC, ML
├── figures/                # Plots and visuals used in thesis and slides
├── thesis/                 # LaTeX source for the full thesis document
├── slides/                 # Beamer presentation files
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```bash
## 🚀 Getting Started
1. Clone the Repository

git clone https://github.com/data-lab01/MScIS.git
cd MScIS

python3 -m venv thesis
source these/bin/activate
pip install -r requirements.txt

2. Set Up Python Environment

python3 -m venv thesis
source thesis/bin/activate
pip install -r requirements.txt

3. Run Simulations and ML Correction
cd scripts/
python 1_Normal-sensor_data.py
python 2_corrupt_sensor_data.py
python 3_MCMC_simulation.py
python 4_ML-Based Anomaly Detection and Correction.py


4. View Grafana Dashboard

Ensure InfluxDB and Grafana are running (via Docker or local installation) and configured properly for effective pipelines.

📚 References

Key references include:
    Brooks et al. (2011). Handbook of Markov Chain Monte Carlo. CRC Press.
    Robert & Casella (2013). Monte Carlo Statistical Methods. Springer.
    Blundell et al. (2015). Weight Uncertainty in Neural Networks. ICML.
    Hoffman & Gelman (2014). The No-U-Turn Sampler. JMLR.
