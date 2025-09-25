COVID-19 Data Analysis 🦠📊
- 📌 Overview

This project explores Italy's COVID-19 data through exploratory data analysis (EDA), statistical methods, and visualization. The goal is to identify trends in infections, recoveries, deaths, and testing patterns, and to derive insights that can help understand the dynamics of the pandemic.

- 📂 Project Structure
covid19-data-analysis/
│
├── data/
│   └── covid19_dataset.csv           # dataset used for analysis
│
├── notebooks/
│   └── covid19_analysis.ipynb        # Jupyter Notebook with full analysis
│
├── results/
│   └── plots/                        # visualizations generated
│
├── README.md                         # project overview
└── report.pdf                        # optional detailed report

- 🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) – for data cleaning and visualization

Jupyter Notebook – interactive exploration

SQL (optional) – if used for queries

Power BI / Tableau (optional) – dashboards for insights

- 📊 Dataset

The dataset includes COVID-19 statistics such as:

Date of report

Hospitalized cases (with symptoms, intensive care, total)

Home confinement

Cumulative positive cases and daily new cases

Recovered and deaths

Total tests, people tested, molecular & antigen test counts

Clinical activity and survey results

- 🔍 Key Analysis Performed

Time-series trends of confirmed, recovered, and death cases

Hospitalization and ICU demand over time

Recovery and fatality rates

Testing patterns and positivity rates

Correlation between testing and new cases

Visualization of flattening curves for total cases and deaths

- 📈 Key Insights & Conclusions

The number of recoveries has increased alongside the rise in total cases.

There is still a need to flatten the curve of total cases.

While the number of deaths is rising, signs of curve flattening are beginning to appear.

- 🚀 How to Run

Clone the repository:

git clone https://github.com/Zer0-to-1/covid19-data-analysis.git
cd covid19-data-analysis


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook notebooks/covid19_analysis.ipynb

- 📄 Report

The full project report (PDF) includes:

Queries and methods used

Visual outputs (charts/plots)

Results and conclusions

- 🎯 Outcomes

Strengthened skills in data wrangling, visualization, and statistical analysis

Derived actionable insights from a real-world health dataset

Demonstrated ability to communicate findings through plots and reports

- 🙌 Acknowledgments

This project was completed as part of my Applied Data Analytics journey.
