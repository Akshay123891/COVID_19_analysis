# 🦠 COVID-19 Data Analysis Project

This project is part of **Module 12 - Assignment 5** of the Data Science curriculum. It involves exploring the impact of the COVID-19 pandemic using real-world datasets, and analyzing its correlation with global happiness indicators such as GDP, life expectancy, and social support.

---

## 📁 Datasets Used

1. **COVID-19 Confirmed Dataset**  
   - `covid19_Confirmed_dataset.csv`  
   - Daily confirmed COVID-19 cases by country.

2. **COVID-19 Deaths Dataset**  
   - `covid19_deaths_dataset.csv`  
   - Daily death counts by country.

3. **Worldwide Happiness Report**  
   - `worldwide_happiness_report.csv`  
   - Contains happiness metrics: GDP per capita, social support, life expectancy, etc.

---

## 🔍 Project Objectives

- Load and preprocess the COVID-19 and Happiness datasets.
- Aggregate and clean the COVID-19 data by country.
- Merge COVID data with happiness metrics.
- Visualize key relationships using scatter plots and regression plots.
- Analyze trends and generate insights through correlation analysis.

---

## ⚙️ Technologies Used

- Python 🐍
- Jupyter Notebook 📒
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 📊 Key Steps Performed

### ✅ Data Preprocessing

- Cleaned confirmed and deaths datasets by dropping unnecessary columns.
- Aggregated latest confirmed and death counts per country.
- Cleaned and selected relevant happiness metrics.
- Merged COVID-19 and happiness data on the country level.

### ✅ Visualizations

- **Scatter Plot:** Confirmed cases vs Deaths  
- **Regression Plot:** Confirmed cases vs Deaths  
- **Correlation Heatmap:** Confirmed, Deaths, Recovered, GDP, Life Expectancy, Social Support

---

## 📌 Insights

- Strong positive correlation between confirmed cases and deaths.
- GDP and social support show varied relationships across countries in terms of COVID impact.
- Countries with higher health and happiness indicators generally managed better outcomes.

---

## 📎 How to Run

1. Clone this repo or download the `.ipynb` notebook.
2. Place the three CSV files in the same directory:
   - `covid19_Confirmed_dataset.csv`
   - `covid19_deaths_dataset.csv`
   - `worldwide_happiness_report.csv`
3. Open the notebook in Jupyter.
4. Run all cells step-by-step to explore the analysis.

---

## 📂 Folder Structure
covid19-analysis-project/
│
├── covid19_Confirmed_dataset.csv
├── covid19_deaths_dataset.csv
├── worldwide_happiness_report.csv
├── COVID-19 Analysis.ipynb
└── README.md
