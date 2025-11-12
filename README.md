# 🌞 Solar Challenge — Week 0

This repository contains the setup for **Week 0** of the Solar Challenge.  
It includes:
- A Python virtual environment configuration
- Dependency installation instructions
- A GitHub Actions workflow for Continuous Integration (CI)

---

## 📦 Project Setup

Follow the steps below to set up this project locally.

### 1. Clone the Repository
    git clone https://github.com/Mekd7/solar-challenge-week0.git
    cd solar-challenge-week0

### 2. Create a Virtual Environment
    python -m venv venv

### 3. Activate the Virtual Environment

    venv\Scripts\activate
    
### 4. Install Dependencies

    pip install -r requirements.txt

# 🔍 Task 2: EDA: Sierra Leone Solar Data

This project includes exploratory data analysis of solar energy and environmental variables in Sierra Leone.

The goal of the EDA is to:

   -  Understand solar irradiation levels across different regions
   -  Examine weather and atmospheric factors affecting solar energy production
   -  Identify patterns and insights that support future solar investment strategy

## Key Steps in the EDA: 

   - Loaded and cleaned the dataset
   - Checked for missing values and handled inconsistencies
   - Visualized temperature, humidity, solar irradiance, and related trends
   - Generated summary statistics and correlation analysis
   - Identified potential opportunities for solar deployment

## Outputs:

| Result           | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Cleaned dataset  | Ready for modeling and further analysis                  |
| Visualizations   | Time series trends, distributions, regional comparisons  |
| Insights summary | Key findings regarding solar feasibility in Sierra Leone |


The full analysis is available in:
     /notebooks/sierraleone_eda.ipynb

# 🌍 Task 3: Cross-Country Comparison

## ⚙️ Setup and Execution
    1. Dependencies: Ensure pandas, numpy, matplotlib, seaborn, and scipy are installed.
    2. Execution: Run all cells in the Jupyter Notebook: notebooks/compare_countries.ipynb.
    
The notebook fulfills all requirements by generating the following outputs:

## ✅ Key Deliverables
      - Summary Table: Mean, Median, and Standard Deviation for GHI, DNI, and DHI (Printed/Saved in data/).
      - Boxplots: Side-by-side plots for GHI, DNI, and DHI comparing the three countries (Saved in figures/).
      - Statistical Testing: One-way ANOVA and Kruskal-Wallis P-values on GHI (Printed in the notebook).
      - Ranking Chart: Bar chart ranking countries by average GHI (Saved in figures/).
      - Key Observations: A three-bullet point summary of findings (Markdown cell).

