# 📊✨ Crime Data Visualization Dashboard

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Active-brightgreen)
![Visualizations](https://img.shields.io/badge/Charts-Interactive%20%26%203D-orange)

> 🚀 A modern & interactive dashboard exploring Indian crime data through powerful visual analytics.

---

## 📌 **Table of Contents**
- [🎯 Project Goal](#-project-goal)
- [📊 Visualizations](#-visualizations)
- [🛠 Tech Stack](#-tech-stack)
- [📁 Dataset Overview](#-dataset-overview)
- [💡 Future Ideas](#-future-ideas)
- [⚙️ Installation & Run](#️-installation--run)

---

## 🎯 **Project Goal**
Make complex crime statistics **interactive, beautiful, and easy to explore**:  
✔ Compare crime trends over time  
✔ Discover correlations between crimes & population  
✔ Drill down by state, crime type, and year  
✔ Visualize hidden patterns through advanced 3D & animated charts

---

## 📊 **Visualizations Included**

### 🟩 Correlation Heatmap
- 🔍 Find hidden relationships between crime types & demographic metrics
- ✅ Seaborn heatmap with annotated correlation coefficients
- 📌 Highlights strong & weak correlations visually

---

### 📈 Dual-Axis Line Chart
- Compare two trends on the same timeline with different Y-axes
- *Example:* YEAR vs. FEMALES(per_100k) + RAPE(per_100k)
- Helps answer: _Does rape rate rise with female population?_

---

### 🟢 Scatter Plot: Females vs. Rape Rate
- Bubble chart colored by `STATE/UT`
- Bubble size by total population
- Hover to explore state-wise details

---

### 📅 Time-Series Line Charts
- YEAR vs. TOTAL IPC CRIMES(per_100k)
- YEAR vs. RAPE(per_100k) + DOWRY DEATHS(per_100k)
- Track crime evolution over decades

---

### 🧊 **3D Interactive Scatter Plot** *(Plotly)*
- **Axes:** DACOITY, ROBBERY, AUTO THEFT (per_100k)
- Bubble size: KIDNAPPING & ABDUCTION rate
- Color: STATE/UT
- 🔄 Rotate, zoom & hover to explore

---

### 🛠 Custom 3D Crime Chart
- Compare DACOITY, ROBBERY, AUTO THEFT, BURGLARY across states
- Fully interactive: rotate, zoom, hover
- Helps spot outlier states & crime patterns

---

## 🛠 **Tech Stack**
- **Python** – main language
- **Pandas** – data cleaning & manipulation
- **Matplotlib & Seaborn** – static & correlation plots
- **Plotly** – interactive & 3D visualizations
- **Jupyter Notebook** – analysis workflow

---

## 📁 **Dataset Overview**
- Indian crime data (multiple years, states)
- Demographic data: MALES, FEMALES, POPULATION
- Crime data: DACOITY, ROBBERY, RAPE, AUTO THEFT, BURGLARY, etc.
- Both raw counts & rates (per 100k population)

---

## ✨ **Future Ideas**
- 📊 Animated charts over `YEAR` to show crime trends dynamically
- 🗺 Geo heatmaps by state/region
- 🔮 Predictive modeling & forecasting
- 🖥 Build a web dashboard using Dash or Streamlit

---

## ⚙️ **Installation & Run**
```bash
# Clone repo
git clone https://github.com/your-username/crime-visualization.git
cd crime-visualization

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook or Python scripts
jupyter notebook
