# Assignment 1 – Exploratory Data Analysis

## 📘 Task  
Perform an **exploratory data analysis** on animal shelter datasets from Austin, Texas.  
Data included animal **intakes**, **outcomes**, and optionally **locations** (stray animals data).  
The task required data preparation, descriptive statistics, and answering both given and own questions using **visualization and interpretation**.  

## 🔬 Approach  
- **Data Preparation:**  
  - Loaded and explored datasets (`intakes.csv`, `outcomes.csv`, `locations.csv`)  
  - Cleaned data: handled missing values, removed duplicates, dropped redundant columns  
  - Converted categorical columns  
  - Converted ages to numeric  
  - Converted dates to datetime  
  - Feature engineering: extracted Year/Month, created Age Group bins, normalized At AAC (Austin Animal Center) to Yes/No  

- **Descriptive Statistics & Visualization:**  
  - **Univariate:** distributions of age, intake time, animal type, intake type, sex (histogram, boxplot, countplot, pie chart)  
  - **Bivariate:** relation between intake condition and outcome type (heatmaps)  

- **Given Questions:**  
  - Outcome type vs intake type → strong dependence  
  - Adoption vs age → adoption rates decline with age  
  - Seasonality → intakes peak in May–June, lower in winter  

- **Own Questions:**  
  - Age distribution by Animal Type (from locations dataset)  
  - Shelter vs Volunteers (At AAC) → distribution of animals’ placement  

## 📊 Results  
- Cleaned datasets enabled meaningful statistical summaries and visualizations  
- Found clear **age effect on adoption probability**  
- Identified **seasonal intake patterns**  
- Confirmed **dependence between intake type and outcome type**  
- Own analyses provided deeper insight into age/type structure  

---

## 📂 Files  
- `exploratory_data_analysis.ipynb` – Jupyter notebook with full solution  
- `intakes.csv`, `outcomes.csv`, `locations.csv` – datasets used
