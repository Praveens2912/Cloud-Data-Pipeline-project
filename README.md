# Cloud-Data-Pipeline-project

# Project Title:
Cloud Data Pipeline with AWS, Snowflake, and Power BI

*Project Overview**

This project demonstrates a complete cloud-based data pipeline where I:

-  Obtained data from **AWS S3**
-  Loaded it into **Snowflake** using external stages and storage integration
-  Built an interactive **Power BI dashboard** by connecting directly to the Snowflake warehouse

---

## 🔧 Tools & Technologies

| Tool        | Purpose                                 |
|-------------|------------------------------------------|
| **AWS S3**      | Cloud storage for raw data               |
| **Snowflake**   | Cloud data warehouse + SQL processing    |
| **Power BI**    | Business intelligence & visualization    |
| **SQL**         | For table creation and data transformation |
| **IAM Role & Storage Integration** | Secure connection between Snowflake and AWS |

---

##  Project Steps

### 1. **Data Storage in AWS S3**
- Raw dataset uploaded to an S3 bucket (e.g. `s3://dataanalyticspowerbi.projects/`)

### 2. **Snowflake Integration**
- Created a Snowflake **Storage Integration** with a trusted AWS IAM Role
- Defined an **external stage** pointing to the S3 bucket
- Created a table and used `COPY INTO` to load data into Snowflake:

```sql
COPY INTO schema.table
FROM @stage
FILE_FORMAT = (TYPE = 'CSV' FIELD_DELIMITER = ',' SKIP_HEADER = 1)
ON_ERROR = 'CONTINUE';
```

### 3. Power BI Connection
Used Snowflake connector in Power BI

Imported tables and built custom visualizations

Applied filters, slicers, and dynamic charts for analysis

### Dashboard Highlights
KPI cards, bar charts, and slicers for drill-down analysis
Live connection to Snowflake for real-time data updates





 Snowflake-PowerBI-Project/
├── data/                # Sample or dummy dataset (optional)
├── assets/              # Dashboard screenshots
├── Snowflake_SQL.sql    # SQL commands for table, stage, and copy
├── PowerBI_Dashboard.pbix
└── README.md


###  Security Notes
Access between Snowflake and AWS is secured using:

IAM role with read-only permission to the S3 bucket

Trusted policy and External ID to allow Snowflake to assume the role

###  Key Learning Outcomes
End-to-end data flow from cloud storage to visualization

Hands-on with Snowflake SQL, S3 integration, and BI tools

Cloud security via IAM role-based access
