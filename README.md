# Excel Coffee Sales Dashboard

##  Project Overview
This project contains an interactive Excel dashboard built using a coffee sales dataset consisting of three tables — Orders, Customers, and Products.  
The objective of this project was to clean, transform, and analyze the dataset, then design an interactive dashboard that helps visualize sales performance across customers, products, and regions.



## Data Preparation & Transformation

The following data cleaning and preparation steps were performed:

###  Column Lookups & Data Mapping
- Used VLOOKUP and XLOOKUP to fetch:
  - Customer Name  
  - Customer Email  
  - Country  
  from the *Customer* sheet into the *Order* sheet.
- Used INDEX + MATCH to extract product details from the *Product* sheet:
  - Coffee Type  
  - Roast Type  
  - Size  
  - Unit Price  

###  New Calculated Fields
- Created a Sales column using:
Sales = Unit Price × Quantity


### Data Standardization
- Converted short codes of Coffee Type and Roast Type to **full descriptive names** using **multiple IF conditions**.
- Applied **data formatting & number formatting** for consistency.
- Checked and removed **duplicate records**.
- Converted ranges into **Excel Tables** for structured referencing.

---




## Dashboard & Visualization

The dashboard was built using:

- Pivot Charts with professional formatting
- Interactive features:
- **Slicers** for drill-down analysis
- **Timeline filter** for date-based filtering
- Custom formatting for visual clarity



## Key Features

- Automated lookups using Excel functions
- Clean and structured data model
- KPI-driven sales calculations
- Interactive filters and timeline
- Clear visual storytelling through charts



## Tools & Functions Used

- Microsoft Excel
- VLOOKUP / XLOOKUP
- INDEX + MATCH
- IF & Nested IF conditions
- Pivot Tables & Pivot Charts
- Slicers & Timeline
- Data Cleaning & Formatting



## Outcome & Insights

The dashboard helps analyze:

- Sales trends by product and roast type
- Region-wise and customer-wise performance
- Product mix and revenue contribution

This project demonstrates my ability to:
- Clean and model raw datasets
- Perform lookup-based data integration
- Build analytical dashboards in Excel
- Present insights through interactive visuals


