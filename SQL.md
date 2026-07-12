# World (MySQL)

## 🔹 Project Overview

This project uses **MySQL** to analyse the **World** relational database and explore global population, geographical, and economic trends.

The analysis focused on:

- Population comparisons between countries and cities
- Demographic trends such as population distribution and life expectancy
- Economic analysis including GDP per capita comparisons
- Identifying patterns within country and city data

---

## 🔹 Dataset

**World Database**

- **Source:** Provided via bootcamp
- **Database Tables:**
  - Country
  - City
  - CountryLanguage

The database contains global information stored across three related tables, enabling analysis of countries, cities, languages, populations, and economic indicators.

---

## 🔹 Data Preparation

The following steps were completed during the analysis:

| Process | Description |
|---------|-------------|
| Database Exploration | Reviewed the database schema and relationships between tables |
| Data Understanding | Examined tables, columns, data types, and available information |
| Query Development | Wrote SQL queries to answer business questions |
| Data Analysis | Applied filtering, grouping, aggregation, and sorting techniques |
| Results Review | Analysed query outputs to identify trends and patterns |

---

## 🔹 Analysis

The analysis involved:

- Filtering records using `WHERE`
- Aggregating data using `COUNT()`, `AVG()`, `MAX()`, and other aggregate functions
- Grouping results using `GROUP BY`
- Sorting data using `ORDER BY`
- Working with relational tables to analyse connected data
- Comparing countries, cities, and economic indicators

<p align="center">
  <img src="WHERE-population-is-bigger-than-avg.png" alt="SQL query" width="800">
  <br>
  <em>Population is greater than average population of all cities</em>
</p>

I used the WHERE clause to return all the cities that have a population that is bigger than the average population of all the cities, 

<p align="center">
  <img src="country-highest-lifeexpectancy.png" alt="ORDER BY SQL query" width="800">
  <br>
  <em>Country with highest life expectancy</em>
</p>

I used the ORDER BY clause in this query to return the country with the highest life expectancy, 


---

## 🟦 Population Analysis

I analysed city populations to identify the largest population centres within the database.

The results showed that:

- **New York City** had the largest population, with over **8 million** residents.
- **New South Wales** followed with approximately **3 million** residents.
- **Newmaa** had a population of over **500,000** residents.


![Population Analysis](images/population-analysis.png)

**Business relevance:**

This analysis demonstrates how SQL can identify major population centres, helping organisations target densely populated markets for marketing, logistics, and business expansion.

---

## 🟦 Economic Analysis

I compared countries using **Gross National Product (GNP)** and other economic indicators.

The analysis showed that countries such as **Luxembourg** and **Switzerland** have significantly higher GNP per capita than much larger economies, including the **United States** and **Japan**.


![Economic Analysis](images/economic-analysis.png)

**Business relevance:**

Comparing economic performance helps organisations identify high-value markets, understand purchasing power, and support investment or expansion decisions.

---

## 📈 Project Queries

### Main Project Image

![SQL Queries](images/mysql-project.png)

---

## 🔹 Key Findings

### 1. Population Analysis

New York City was identified as the largest population centre within the database, followed by New South Wales and Newmaa.

**Business relevance:**

Understanding population distribution helps businesses identify large customer markets and optimise marketing, logistics, and resource allocation.

---

### 2. Economic Analysis

Countries such as Luxembourg and Switzerland recorded higher GNP per capita than much larger economies.

**Business relevance:**

Economic comparisons help organisations evaluate market potential, purchasing power, and opportunities for international expansion.

---

## ✅ Conclusion

This project demonstrates my ability to use **MySQL** to query relational databases, analyse population and economic data, apply SQL functions, and generate meaningful insights through filtering, aggregation, grouping, and sorting techniques.
