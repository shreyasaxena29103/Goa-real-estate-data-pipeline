# Goa-real-estate-data-pipeline
End-to-end **data engineering pipeline** built in Databricks using Medallion architecture to process and analyze real estate listings in Goa.
#  Real Estate Data Pipeline (Goa)


##  Project Workflow
1. **Data Ingestion:** Scraped real estate listings from online real-estate sources.
2. **Bronze Layer:** Raw data stored in Azure Blob Storage.
3. **Silver Layer:** Cleaned and deduplicated data using PySpark.
4. **Gold Layer:** Enriched data with latitude and longitude (using Nominatim API) and prepared aggregated tables for Power BI dashboard.
5. **Visualization:** Power BI dashboard showing price distributions, BHK trends, and investment hotspots.



##  Tech Stack
- **Azure Databricks**
- **Azure Blob Storage**
- **PySpark**
- **Nominatim API**
- **Power BI**
- **Delta Lake**

---

##  Dashboard Preview
![Dashboard Screenshot](powerbi/dashboard_screenshot.png)

---
## Files in This Repository
`raw_data.csv` : The raw and scraped data <br>
`real_estate_data_pipeline.ipynb` : Complete Databricks notebook for the entire data pipeline <br>
`architecture/medallion_architecture.png` : Pipeline architecture diagram <br>
'cleaned_data.csv' : The final cleaned dataset
`powerbi/dashboard_screenshot.png` : Power BI dashboard preview
