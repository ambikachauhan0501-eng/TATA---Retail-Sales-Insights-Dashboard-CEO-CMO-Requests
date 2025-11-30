# TATA-Retail-Sales-Insights-Dashboard-CEO-CMO-Requests
This project involves analyzing the **Online Retail dataset** to generate actionable insights requested by the CEO and CMO.   
The analysis was performed using **Tableau / Power BI**, with a focus on data cleaning, visualization, and dashboard creation.  
The final deliverables include four visuals addressing specific business questions around revenue, customer behavior, and product demand.

##  Data Preparation
Before analysis, the dataset was cleaned to ensure accuracy and reliability:
- Removed returns with **negative quantities**.  
- Excluded records where **Unit Price < $0**.  
- Applied conditional formulas and data transformation methods to filter out invalid data.  
- Saved the cleaned dataset for further analysis.


## Visuals Created

### **Question 1 – Revenue Time Series (CEO)**
- Visual: Line chart of **monthly revenue for 2011**.  
- Purpose: Identify seasonal trends and patterns to support forecasting for the next year.  

### **Question 2 – Top 10 Countries by Revenue (CMO)**
- Visual: Bar chart showing **top 10 countries by revenue and quantity sold**.  
- Exclusion: United Kingdom removed from analysis.  
- Purpose: Highlight international markets driving sales.  

### **Question 3 – Top 10 Customers by Revenue (CMO)**
- Visual: Bar chart ranking **top 10 customers by revenue** (descending order).  
- Purpose: Identify high‑value customers for targeted engagement and retention strategies.  

### **Question 4 – Product Demand by Country (CEO)**
- Visual: Global view of **product demand across countries**.  
- Exclusion: United Kingdom removed.  
- Purpose: Identify regions with highest demand to support expansion strategy.  


## Dashboard
- Combined **Question 1 & Question 2 visuals** into a dashboard.  
- Configured **factory/country chart as a filter** → selecting a country filters the device type/customer view.  
- Screenshot of the dashboard with the **highest downtime / demand region** selected included in submission.  


## Learning Objectives
- Practice **data cleaning** and transformation.  
- Build **interactive dashboards** in Tableau/Power BI.  
- Apply **business logic** to define metrics and insights.  
- Communicate findings through clear visualizations.  


## Tools & Technologies
- Tableau Desktop (Packaged Workbook `.twbx`)  
- Power BI Desktop (`.pbix`)  
- Online Retail Dataset (UCI Machine Learning Repository)  
- Excel / CSV for preprocessing  

## 🚀 How to Reproduce
1. Download the Online Retail dataset.  
2. Import into Tableau or Power BI.  
3. Apply data cleaning rules:  
   - Quantity ≥ 1  
   - Unit Price ≥ 0  
4. Create visuals on separate sheets/tabs named **Q1, Q2, Q3, Q4**.  
5. Build dashboard combining Q1 & Q2 with filter functionality.  
6. Save as `.twbx` (Tableau) or `.pbix` (Power BI).  

## 📑 Deliverables
- Cleaned dataset (CSV/Excel).  
- Tableau Packaged Workbook (`.twbx`) or Power BI file (`.pbix`).  
- Dashboard screenshot highlighting insights.  
- README documentation (this file).  

