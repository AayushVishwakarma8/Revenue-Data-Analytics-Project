# Revenue Analysis Dashboard  

## Introduction  
This project is an interactive dashboard designed to visualize and analyze land revenue data across various U.S. states and counties. The dashboard helps users explore trends in revenues generated from land leases, commodities, and products. It provides insights through metrics such as total revenues, revenue types, and the contribution of commodities.  

---

## Project Type  
### PowerBI connection with MySQL server

This project involves data exploration, transformation, database integration, and dashboard creation using the following tools:  
  - Python (Pandas): For data cleaning and transformation.  
  - MySQL: For structured database storage and querying.  
  - Power BI: This is used to create interactive dashboards and visualizations.  

---

## Directory Structure  
```
Revenue_Analysis/
├─ scripts/
│  ├─ data_cleaning.py
│  ├─ mysql_integration.py
├─ reports/
│  ├─ dashboard.pbix
│  ├─ data_analysis_report.pdf
├─ data/
│  ├─ pyproject.csv
│  ├─ transformed_data.sql
├─ README.md
├─ requirements.txt
```

---

## Features  
This project offers the following capabilities:  
  - Data Cleaning and Exploration:  
  - Handled missing values, standardized columns, and prepped data for analysis.  
  -  Filtered data for specific years, states, and commodities.  

  Database Integration:  
    - Transformed data was stored in a MySQL database for querying and organization.      

  Interactive Visualizations:  
    - Developed Power BI dashboards to display revenue trends, state-wise contributions, and commodity-based revenue.  
    - Visualizations include bar charts, line graphs, and geographic maps.  

---

## Installation & Getting Started  

To set up the project locally, follow these steps:  

### Clone the Repository  
```bash  
git clone https://github.com/your-username/Revenue_Analysis.git  
cd Revenue_Analysis  
```  

### Install Dependencies  
```bash  
pip install -r requirements.txt  
```  

### Data Transformation and Integration  
1. Load the dataset:  
   ```python  
   import pandas as pd  
   data = pd.read_csv('data/pyproject.csv')  
   ```  
2. Run the data cleaning script:  
   ```bash  
   python scripts/data_cleaning.py  
   ```  
3. Import the transformed data into MySQL using the provided SQL script:  
   ```bash  
   mysql -u username -p < data/transformed_data.sql  
   ```  

### Open the Dashboard  
- Load the `dashboard.pbix` file in Power BI Desktop to explore visualizations.  
- Or access the deployed version online through the provided link.  

---

## Technology Stack  
  - Python: Backend logic for data processing and transformation.  
  - Pandas: For data manipulation and cleaning.  
  - MySQL: This is for database storage and querying.  
  - Power BI: This is for building dashboards and visualizations.  

---

## Key Dates and Activities  

  12th November:
   -  Planning and understanding the data
    
  13th November:
    - Initial data exploration and cleaning.  
    - Set up MySQL database for storing structured data.  

  14th November:
    - Created Power BI dashboards with interactive visualizations.
    
  15th November:
    - Created Power BI dashboards with interactive visualizations.

  16th November:
    - Finalized the dashboard and deployed the Power BI report.  

---

## Usage  
Once the dashboard is live:  
  - Use filters to explore data by Year and state.  
  - Gain insights into revenue trends, top-performing commodities, and geographic revenue distributions.  

---

## logo
![WhatsApp Image 2024-11-12 at 21 00 15_ccd17d9f](https://github.com/user-attachments/assets/1ecf0e8e-a6df-483a-987c-d597e9b776cf)

