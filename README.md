# 🌦️ Snowflake + AWS + Power BI Project – Rainfall & Crop Yield Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?logo=powerbi&logoColor=black)
![Snowflake](https://img.shields.io/badge/Snowflake-Cloud%20Data%20Warehouse-29B5E8?logo=snowflake&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud%20Storage%20%26%20ETL-FF9900?logo=amazonaws&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Data%20Extraction-4479A1?logo=postgresql&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analytics-1E8449)
![Dashboard](https://img.shields.io/badge/Interactive-Dashboard-FF6F00)
![Cloud](https://img.shields.io/badge/Cloud-Computing-0089D6?logo=microsoftazure)
![Domain](https://img.shields.io/badge/Domain-Agriculture-blueviolet)

---

## 📘 Project Overview
This project demonstrates an **end-to-end multi-cloud analytics pipeline** integrating **AWS**, **Snowflake**, and **Power BI**.  
The objective was to analyze **20 years of climate and agricultural data (2000–2020)** to understand how **rainfall, temperature, humidity, and other environmental factors** influence **crop yield** across different regions and seasons.

Data was first ingested and stored in **AWS (Amazon Web Services)** using **S3 buckets** for scalable and reliable cloud storage.  
From there, data was transferred to **Snowflake Cloud Data Warehouse** for SQL-based data modeling and aggregation.  
Finally, the cleaned and transformed data was visualized in **Power BI**, providing a dynamic dashboard to uncover actionable insights into climate and agricultural performance.

This project showcases how **AWS, Snowflake, and Power BI** can work together to deliver a **scalable, automated, and insight-driven data pipeline** for large datasets.

---

## 🎯 Objectives
- Analyze **average rainfall, temperature, and humidity** over time.  
- Study **crop-wise and region-wise yield variations**.  
- Identify high-performing regions and crop combinations.  
- Build a **multi-cloud pipeline** integrating AWS, Snowflake, and Power BI.  
- Develop a unified **dashboard for agricultural monitoring and insights**.  

---

## ⚙️ Tools & Technologies
| Tool | Purpose |
|------|----------|
| **AWS (S3)** | Cloud storage for raw data files and ingestion layer |
| **Snowflake** | Cloud-based data warehouse for data transformation and querying |
| **Power BI** | Data modeling, visualization, and dashboard creation |
| **SQL** | Querying and aggregating datasets in Snowflake |
| **Power Query** | Data cleaning and transformation in Power BI |
| **Excel** | Dataset verification and preprocessing reference |

---

## 🧩 Data Preparation
- Data was uploaded to **AWS S3** for secure and centralized storage.  
- Connected Snowflake to AWS S3 using **Snowpipe** for continuous data ingestion.  
- Performed SQL-based transformations in **Snowflake** to clean, aggregate, and model the data.  
- Used **Power BI’s Snowflake connector** for live data visualization.  
- Implemented **Power Query** for additional data shaping, column renaming, and missing-value handling.  
- Created calculated DAX measures for seasonal and yearly yield comparisons.

---

## 📊 Dashboard Highlights

### ☔ Rainfall Analysis
- Annual and seasonal rainfall variations (Rabi, Kharif, Zaid)  
- Crop-wise rainfall averages (Paddy, Tea, Coffee, Ginger)  
- Regional rainfall comparison (Bangalore, Raichur, Kodagu, Mangalore)

### 🌡️ Temperature Analysis
- Crop and season-based temperature patterns  
- Regional heat map of temperature differences  

### 💧 Humidity Analysis
- Seasonal humidity stability across regions  
- Comparative analysis of crop performance in varying humidity conditions  

### 🌾 Yield Analysis
- Crop yield by season and location  
- Top 10 high-yield crops (Cotton, Coconut, Ginger, Tea, etc.)  
- Yield correlation with climatic patterns and rainfall distribution  

---

## 📈 Key Insights
- **AWS S3 + Snowflake pipeline** ensured fast, secure, and scalable data ingestion.  
- **Kodagu and Mysuru** emerged as high-yield regions due to optimal rainfall and temperature conditions.  
- **Cotton and Coconut** maintained the highest productivity rates over multiple years.  
- **Rainfall consistency** directly influenced higher yields in Rabi and Kharif seasons.  
- Power BI’s dynamic visuals allowed cross-regional and crop-level yield comparison with real-time updates.

---

## 🧠 Learnings
- Built a **multi-cloud architecture** using AWS for storage, Snowflake for warehousing, and Power BI for BI visualization.  
- Gained hands-on experience in **Snowpipe data ingestion** from AWS S3 into Snowflake.  
- Strengthened knowledge in **DAX and Power Query** for creating custom KPIs and trend-based visuals.  
- Understood how cloud ecosystems can work together for **real-world data analytics solutions**.


---

## 🏁 Conclusion
This project showcases a **multi-cloud analytics ecosystem** that combines **AWS for storage**, **Snowflake for scalable data processing**, and **Power BI for powerful visualization**.  
By automating the data pipeline from AWS S3 to Snowflake and then Power BI, it delivers **real-time insights** into the relationship between climate patterns and crop yield performance.  
It highlights how modern cloud tools can be integrated to create **data-driven agricultural intelligence systems** with high performance and scalability.

---

### 🏷️ Tags  
`#PowerBI` `#Snowflake` `#AWS` `#CloudDataWarehouse` `#DataAnalytics` `#DAX` `#PowerQuery` `#AgricultureAnalytics` `#PortfolioProject`


