# US Data Case Study — MySQL

## Overview
This project involves importing multiple U.S. public datasets into a MySQL database and writing SQL queries to analyze relationships across weather, air quality, demographics, voting, incarceration, and education data.

**Assumption:**  
If a date is not explicitly provided in a dataset, assume the data is from **2018**.

---

## Datasets

Download the following six CSV files:

1. **US States.csv**
2. **Daily Weather.csv**
3. **US Voter Registration and Demographics By State.csv**
4. **Air Quality Index by US County.csv**
5. **US Incarcerated Population, Per Race, Ethnicity, and Region.csv**
6. **AP Computer Science Test Taker Demographics by State.csv**

---

## Database Setup (MySQL Workbench)

### 1. Create Schema
Create a new schema named:

```sql
us_database
