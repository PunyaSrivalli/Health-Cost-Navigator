# Health-Cost-Navigator

---

## 🔄 Workflow Overview

1. **Data Collection**: Download JSON price transparency files from hospital sites.
2. **Data Parsing**: Convert JSON to structured CSVs.
3. **Cleaning**: Standardize column names, drop duplicates, handle nulls.
4. **Transformation**: Convert wide format to long for effective modeling.
5. **Loading**: Use Snowflake for scalable and secure data storage.
6. **Visualization**: Build Streamlit app to interact with hospital pricing insights.

---

## 🌐 Covered Regions

- Charlotte-Concord-Gastonia, NC-SC
- Chicago-Naperville-Elgin, IL-IN-WI
- Las Vegas-Henderson-Paradise, NV

---

## 📊 Key Insights

- **UnitedHealthcare**, **Aetna**, and **Cigna** lead in total charges.
- Ambetter and Medicare Advantage show highest average charges in Naperville.
- Query latency maintained under 10 seconds on Snowflake.

---

## 🚀 Streamlit Dashboard Features

- 🔍 Search by **CPT code**, **ZIP code**, or **City**
- 🏥 Compare prices across hospitals
- 📉 Visualize and sort charges in ascending/descending order
- 📊 Interactive charts and tables powered by Snowflake-backed queries

---

## 🧠 Technologies Used

- **Snowflake** (Data Warehousing & Processing)
- **Python** (Data Cleaning & Integration)
- **Streamlit** (Frontend UI)
- **Jupyter Notebooks** (ETL Scripts)
- **SQL** (Dashboards & Data Aggregation)

---

## 📈 Ingestion Metrics

| Metric | Value |
|--------|-------|
| Rows Processed | 2M+ |
| Unique CPT Codes | ~38,800 |
| Hospitals Analyzed | 17 |
| Insurance Providers | 160+ |
| Query Latency | <10s |

---

This project is for academic use only. Not intended for commercial or clinical decisions.

