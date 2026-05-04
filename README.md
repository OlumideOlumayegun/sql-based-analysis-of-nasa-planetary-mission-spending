# 🚀 SQL-Based Analysis of NASA Planetary Mission Spending

![banner_image](/images/banner_image.png)

## 📌 Overview

This project explores NASA’s planetary exploration budgets using SQL. By analysing mission-level financial data across multiple decades, the project uncovers trends in spending, identifies high-cost missions, and highlights how investment priorities have shifted over time.

The analysis includes inflation-adjusted calculations to ensure meaningful comparisons across different time periods.

---

## 🎯 Objectives

* Calculate total mission spending across all years
* Adjust historical costs for inflation
* Identify the most expensive missions
* Analyse spending trends over time
* Examine budget allocation by destination
* Combine time and destination for deeper insights

---

## 🗂️ Dataset

The dataset used in this project was provided by DataCamp and is based on publicly available NASA mission budget data (originally sourced from The Planetary Society).

### Key Tables:

* **`mission_budgets`** – Yearly mission cost data
* **`inflation`** – Inflation adjustment factors
* **`mission_details`** – Mission metadata (destination, program, etc.)

---

## 🛠️ Tech Stack

* **SQL** – Core analysis and data transformation
* **Python (Jupyter Notebook)** – Workflow and visualisation
* **Plotly Express** – Data visualisation

---

## 📊 Key Insights

* NASA’s planetary exploration spending exceeds **$100B+ (inflation-adjusted)**
* Spending is **cyclical**, often aligned with major mission launches
* **Mars and outer planet missions** dominate long-term investment
* Early spending focused heavily on the **Moon (Space Race era)**
* Budget priorities have shifted toward **diversified planetary exploration**

---

## 📈 Example Visualisations

### Spending Over Time

![Spending Over Time](/images/spending_over_time.png)

### Spending by Destination Over Time

![Spending by Destination](/images/spending_by_destination.png)

---

## 📂 Project Structure

```
├── notebook.ipynb          # Main analysis notebook
├── data/                   # (Optional) dataset files
├── images/                 # Visualisations
└── README.md               # Project documentation
```

---

## 🙌 Acknowledgements

This project was completed as part of a guided exercise on DataCamp.

Thanks to DataCamp for providing the cleaned dataset and structured guidance that made this analysis possible.

