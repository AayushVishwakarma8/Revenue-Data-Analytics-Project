# Revenue Analysis Dashboard  

## Introduction  
This project is an interactive dashboard designed to visualize and analyze land revenue data across various U.S. states and counties. The dashboard helps users explore trends in revenues generated from land leases, commodities, and products. It provides insights through metrics such as total revenues, revenue types, and the contribution of commodities.  

---

## Project Type  
 Data Analysis and Dashboarding connecting with MySQL  

This project involves data exploration, transformation, database integration, and dashboard creation using the following tools:  
- Python (Pandas): For data cleaning and transformation.  
- MySQL: For structured database storage and querying.  
- Power BI: For creating interactive dashboards and visualizations.  


---

## Directory Structure  
```
Land_Revenue_Analysis/
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
   - Filtered data for specific years, states, and commodities.  

- Database Integration:  
   - Transformed data was stored in a MySQL database for querying and organization.  
   - Created normalized tables for efficient querying.  

- Interactive Visualizations:  
   - Developed Power BI dashboards to display revenue trends, state-wise contributions, and commodity-based revenue.  
   - Visualizations include bar charts, line graphs, and geographic heatmaps.  

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
- MySQL: For database storage and querying.  
- Power BI: For building dashboards and visualizations.  

---

## Key Dates and Activities  

- 12st November 2024:
   - Planning and Understanding the data
- 13st November 2024:  
   - Initial data exploration and cleaning.  
   - Setup MySQL database for storing structured data.  

- 14th November 2024 and 15th November 2024:  
   - Created Power BI dashboards with interactive visualizations.  

- 16th November 2024:  
   - Finalized the dashboard and deployed the Power BI report.  

---

## Usage  
Once the dashboard is live:  
- Use filters to explore data by **Year** or **State** .  
- Gain insights into revenue trends, top-performing commodities, and geographic revenue distributions.  

---
## Logo
![WhatsApp Image 2024-11-12 at 21 00 15_ccd17d9f](https://github.com/user-attachments/assets/4f3aeeb9-9fef-495e-9af2-848fd1828e77)

