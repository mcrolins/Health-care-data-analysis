# Health-care-data-analysis

This project presents a comprehensive analysis of a health-related survey dataset. The data includes information about individuals' demographics, healthcare access, insurance status, hospital visits, and preventive health behaviors like routine check-ups and cancer screenings.

## 📊 Objectives

- Clean and preprocess the raw survey data
- Handle missing values appropriately
- Convert categorical and numerical columns into usable formats
- Perform exploratory data analysis (EDA)
- Visualize key trends and distributions
- Derive insights on healthcare access and patterns

## 📂 Repository Structure


health-data-analysis/
│ ├── age_distribution.png
│ ├── insurance_coverage.png
│ └── ...
├── health_data_cleaned.csv # Cleaned version of the dataset
├── analysis.ipynb # Jupyter notebook with full workflow
└── README.md # This file

## 📈 Key Insights

- The majority of respondents are within the age group `41-50`.
- A significant portion of individuals do not have routine check-ups.
- Monthly household income ranges vary but contain many non-numeric ranges like `'20001-30000'`.
- There were many missing values in fields like `Age`, `Marital Status`, and `Income`, which were handled using imputation strategies.

## 🧰 Tools Used

- **Python**
- **pandas**
- **matplotlib**
- **seaborn**
- **Jupyter Notebook**

## 📌 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/health-data-analysis.git
   cd health-data-analysis
   Open analysis.ipynb in Jupyter Lab or VS Code and run the cells.


