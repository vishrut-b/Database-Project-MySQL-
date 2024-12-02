### SQL Project: **"Exploring the White Dwarf Catalog Using SQL"**

---

## **Project Overview**
This project showcases the use of SQL to manage and analyze astrophysical data from the **"White Dwarfs within 25pc of the Sun"** catalog. The goal was to efficiently query, manipulate, and extract valuable insights about white dwarfs using structured SQL commands. The project focuses on leveraging SQL's flexibility to perform data cleaning, exploration, and statistical analysis.

---

## **Key Features**
- **Database Setup:**
  - Extracted and imported data from the Vizier catalog into an SQL database.
  - Created and populated a structured table for the white dwarf dataset.
  - Removed redundant and unnecessary columns to streamline the database.

- **Data Exploration:**
  - Queried specific white dwarfs' coordinates, distances, and other attributes.
  - Identified the farthest white dwarf and unique entries in the dataset.
  - Counted the total number of white dwarfs in the sample.

- **Statistical Analysis:**
  - Calculated the percentage of DA-type white dwarfs within a specified temperature range and distance.
  - Determined the fraction of magnetic white dwarfs in the catalog.
  - Computed the ratio between DA and non-DA magnetic white dwarfs.

---

## **Tools and Technologies**
- **SQL Commands:**  
  - `CREATE TABLE`, `ALTER TABLE`, `SELECT`, `COUNT`, `DISTINCT`, `REGEXP`, and nested subqueries for efficient data handling.
- **Data Source:**  
  - White dwarf dataset sourced from the Vizier catalog.
- **Visualization Tools:**  
  - Aladin for plotting white dwarfs' sky positions.

---

## **Insights Derived**
- **Spatial Data:** Mapped the positions of white dwarfs to analyze their distribution in the sky.  
- **Astrophysical Statistics:**
  - 59.19% of the sample consists of DA-type white dwarfs within the given constraints.
  - 8.56% of the sample are magnetic white dwarfs, aligning with known astrophysical proportions.
  - A computed ratio of 12:7 for DA magnetic to non-DA magnetic white dwarfs.

---

## **Challenges**
- Discrepancies between the catalog's data and the original paper, resulting in slight differences in statistical outcomes.
- Handling and cleaning inconsistencies in the dataset, such as missing or redundant data.

---

## **Usage**
Clone this repository and explore the SQL scripts provided to replicate the queries and analyses:
1. Import the dataset into your SQL environment.
2. Run the scripts sequentially to clean, manipulate, and analyze the data.
3. Modify or expand the queries to explore additional astrophysical insights.

---

## **Conclusion**
This project demonstrates the power of SQL for astrophysical data analysis. By applying structured queries, we uncovered key insights about white dwarfs, showcasing SQL's versatility in handling complex datasets.

---
