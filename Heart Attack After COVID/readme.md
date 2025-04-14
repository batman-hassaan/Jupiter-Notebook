# Heart Attack Analysis & Visualization

This project provides an in-depth analysis and visualization of a real-world healthcare dataset that focuses on the relationship between vaccination, pre-existing health conditions, and heart attack occurrences among patients across India.

## 📋 Dataset Overview
The dataset contains 76 entries and covers the following fields:
- Patient ID
- Age
- Gender
- Vaccination Date
- Vaccine Dose
- Pre-existing Conditions
- Heart Attack Date
- Severity
- Outcome
- Location
- Blood Pressure
- Cholesterol Level
- BMI
- Smoking History
- Diabetes Status

## 🧰 Libraries Used
- `pandas`: For loading and preprocessing the dataset.
- `numpy`: For numerical operations and handling missing values.
- `matplotlib`: For basic plotting.
- `seaborn`: For advanced statistical visualizations.
- `plotly.express`: For interactive visualizations and insights.

## 🔍 Project Objectives
- Clean and preprocess the dataset.
- Analyze correlations between heart attack occurrences and:
  - Pre-existing conditions (e.g. Diabetes, Obesity, Heart Disease)
  - Vaccination status and type (1st Dose, 2nd Dose, Booster)
  - Lifestyle factors (Smoking History, BMI, Blood Pressure, Cholesterol)
- Visualize the severity and outcomes of heart attacks.
- Compare survival rates post-heart attack by gender, age, and location.

## 📊 Sample Visualizations
- Heatmap of Correlations
- Bar Charts showing the frequency of heart attacks by condition
- Pie Charts of survival outcomes
- Line Graphs showing trends over time
- Scatter Plots for BMI vs Cholesterol vs Severity
- Geographical Distribution of heart attack cases using Plotly

## 🚀 How to Run
1. Install required libraries (if not already installed):
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook heart_attat.ipynb
   ```
3. Run all cells to see the data cleaning, analysis, and visualizations.

## 📁 File Structure
```
heart_attack_analysis/
├── heart_attat.ipynb       # Jupyter Notebook with complete analysis
├── README.md               # Project description and usage
```

## 💡 Insights Extracted
- High BMI, very high blood pressure, and cholesterol levels are major factors among heart attack patients.
- People with diabetes, obesity, or smoking habits have a significantly higher risk.
- The 2nd Dose of vaccination appears more common among patients, but correlation doesn't imply causation.
- Survival rates are generally high, especially for mild and moderate cases, with timely intervention.
- Geographic regions like Kolkata, Jaipur, Surat, and Indore have higher reported cases.

## 📌 Future Improvements
- Add machine learning models to predict heart attack risk.
- Use more external data (e.g., daily activity, stress levels).
- Build a dashboard using Dash or Streamlit for real-time exploration.

## 👨‍💻 Author
**Hassaan**  
Contact: [www.linkedin.com/in/hassaanshahid217]
```

This version:
1. Uses proper Markdown formatting with headers
2. Maintains all the original content
3. Improves readability with consistent bullet points
4. Preserves code blocks for commands
5. Uses proper spacing between sections
6. Formats the file structure as a code block

