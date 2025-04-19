# ⚓ Maritime Port Performance Dashboard (2022–2023)

![Maritime Port Dashboard](Port%20Images/Maritime%20Port.PNG)

This project provides data exploration and visualization of port performance statistics using a Streamlit dashboard, based on the UNCTAD dataset for 2022 and 2023.

## 📊 Project Overview

This project explores trends in vessel size, age, port time, and cargo capacity using historical data across different vessel types and time periods. Visualizations and summaries help stakeholders assess maritime port performance and identify potential efficiency gaps.

## 🗂️ Dataset

- Source: UNCTADstat
- Scope: Port call and vessel performance stats (2022–2023)
- Columns include vessel type, period, average vessel age, port time, gross tonnage, cargo and container capacity.

📁 **Available Data**:
- `cleaned_port_performance_2022_2023.csv` — final cleaned dataset used in dashboard and analysis.

## 🧪 EDA Highlights

- **Vessel Age**: Most vessels range between 6–36 years.
- **Port Time**: Container and LNG ships have the shortest turnaround time.
- **Correlations**: Strong link between vessel size (GT) and cargo/container capacity.
- **Period Trends**: Stable metrics across 2022 and 2023 with slight seasonal effects.

## 🌐 Live Dashboard

👉 **[Explore the Streamlit App](https://maritime-port-performance-app-app-chxb78zq8crbdjwxfp8zp6.streamlit.app/)**  
Built using `Streamlit` for interactive data exploration.

## 🚀 Future Work

- Apply clustering to group  vessels based on performance.
- Integrate real-time port traffic or AIS data.
- Explore unsupervised ML models for anomaly detection.

## 📦 Setup Instructions

1. Clone this repo
   ```bash
   git clone https://github.com/FijabiAdekunle/maritime-port-performance-project.git
   cd maritime-port-performance

## 🛠️ Tools & Libraries
- Python, Pandas, Matplotlib, Seaborn

- Streamlit

- Jupyter Notebook

## 📣 Call to Action
If you work in maritime logistics, policy, or analytics — this project could help inform smarter decisions.
Feel free to fork, collaborate, or suggest improvements!

> 🔗 Author: Fijabi J. Adekunle (FJ the Data Explorer)
> 📧 Contact: [LinkedIn](https://www.linkedin.com/in/fijabi-j-adekunle/)
Email: fijaytwo@gmail.com



