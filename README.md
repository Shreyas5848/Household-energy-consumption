# 🔌 Household Energy Consumption Analysis & Clustering

This project explores and analyzes household energy consumption data to identify usage patterns and cluster similar energy consumers (households, warehouses, small-scale industries). It demonstrates how unsupervised learning techniques like K-Means can uncover hidden structures in real-world data, enabling better energy planning, anomaly detection, and efficiency improvements.

---

## 📊 Overview

With the growing demand for sustainable energy, understanding how different households and establishments consume power is vital. This project:

- Performs **exploratory data analysis (EDA)** on energy usage.
- Applies **clustering algorithms (K-Means, DBSCAN)** to group similar consumers.
- Visualizes insights that can help in **demand-side management** and **targeted energy policies**.

---

## 🧰 Tools & Technologies

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn** (K-Means, PCA)
- **Jupyter Notebook**

---

## 🔍 Problem Statement

Given a dataset of energy consumption from various sources (households, warehouses, factories), how can we:

- Analyze and understand consumption patterns?
- Group consumers with similar energy usage profiles?
- Build actionable insights for better energy management?

---

## 📁 Dataset

- Source: [UCI Machine Learning Repository / Kaggle / Other – Add actual source]
- Features include: `timestamp`, `household_id`, `total_energy_kWh`, `appliance_type`, `temperature`, etc.

*(Add a sample snapshot of the dataset here if possible)*

---

## 🧪 Methodology

1. **Data Cleaning**
   - Removed missing or duplicate records.
   - Normalized energy consumption values.

2. **Feature Engineering**
   - Extracted temporal features: hour, day, seasonality.
   - Calculated peak usage windows.

3. **Clustering**
   - Applied **K-Means** with elbow method to find optimal `k`.
   - Visualized clusters using **PCA** and **2D/3D plots**.
   - Interpreted each cluster’s behavior (e.g., high nighttime users, industrial-scale consumers).

---

## 📈 Key Results

- Identified **3 major consumer types**:
  - **Type A**: Consistent low usage – typical households.
  - **Type B**: High peak-hour usage – office spaces.
  - **Type C**: Constant high usage – small factories or warehouses.

- Enabled potential strategies like:
  - Time-of-use pricing
  - Load balancing recommendations
  - Energy-saving alerts for high-consumption clusters

---

## 📸 Visualizations

*(Embed sample plots or add images here – e.g., cluster heatmaps, energy usage timelines, elbow graph for K selection)*

---

## 🚀 How to Run

```bash
git clone https://github.com/Shreyas5848/Household-energy-consumption.git
cd Household-energy-consumption
jupyter notebook
