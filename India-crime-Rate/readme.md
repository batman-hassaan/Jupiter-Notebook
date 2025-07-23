
# 📊 Crime Data Visualization Project

This project visualizes and analyzes crime data across Indian states and years using Python and advanced data visualization libraries.

---

## ✅ **Visualizations Included**

### 1️⃣ Correlation Heatmap
- **Purpose:** Show how different crime types and demographic metrics correlate with each other.
- **Tool:** Seaborn `heatmap`
- **Features:**
  - Dark diagonal line shows perfect correlation (self-correlation)
  - Colored grid indicates strength & direction of correlations
  - Helps find related crime patterns

---

### 2️⃣ Dual-Axis Line Chart
- **Purpose:** Compare two different trends on the same X-axis (YEAR) with two Y-axes.
- **Example:** YEAR vs. FEMALES(per_100k) (left axis) and RAPE(per_100k) (right axis)
- **Tool:** Matplotlib
- **Features:**
  - Tracks population trend vs. crime rate
  - Easy to see if crime rate increased as population changed

---

### 3️⃣ Scatter Plot: Females vs. Rape Rate
- **Purpose:** Analyze relationship between female population density and rape crime rate.
- **Tool:** Seaborn `scatterplot`
- **Features:**
  - Colored by STATE/UT
  - Bubble size by total population
  - Grid and styling for clarity
  - Hover tooltip shows extra data

---

### 4️⃣ Time-Series Line Charts
- **Purpose:** Track crime trends over years.
- **Examples:**
  - YEAR vs. TOTAL IPC CRIMES(per_100k)
  - YEAR vs. RAPE(per_100k) + DOWRY DEATHS(per_100k)
- **Tool:** Matplotlib / Seaborn
- **Features:**
  - Trendlines for individual or multiple crime types
  - Visualize increase/decrease over time

---

### 5️⃣ 3D Interactive Scatter Plot
- **Purpose:** Explore crime data interactively across three crime types.
- **Example:** DACOITY(per_100k) vs. ROBBERY(per_100k) vs. AUTO THEFT(per_100k)
- **Tool:** Plotly
- **Features:**
  - Bubble size by KIDNAPPING & ABDUCTION(per_100k)
  - Colored by STATE/UT
  - Hover tooltips show year, population, burglary rate, etc.
  - Fully interactive: rotate, zoom, pan

---

### 6️⃣ 3D Interactive Crime Chart (Custom)
- **Purpose:** Compare multiple crime types across states in 3D.
- **Example:** DACOITY, ROBBERY, AUTO THEFT, KIDNAPPING & ABDUCTION, BURGLARY
- **Tool:** Plotly Scatter3d
- **Features:**
  - X: crime type
  - Y: state
  - Z: average crime value
  - Colored & hover tooltips for clarity

---

## 📦 **Tech Stack & Libraries**
- Python
- Pandas (data manipulation)
- Matplotlib (static charts)
- Seaborn (heatmaps, scatter plots)
- Plotly (interactive & 3D visualizations)

---

## 📌 **Dataset Overview**
- Indian crime data across multiple years and states.
- Columns include:
  - Population data (MALES, FEMALES)
  - Crime counts & per 100k rates (e.g., DACOITY, ROBBERY, RAPE, BURGLARY, etc.)
  - Year and STATE/UT

---

## ✨ **Future Ideas**
- Animated charts over year
- Crime heatmaps by geographical map
- Interactive dashboard
- Predictive modeling of crime trends

---

> 📍 **Goal:** Make crime data easier to understand, compare, and explore through visual analytics.

