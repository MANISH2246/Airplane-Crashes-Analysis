✈️ Airplane Crashes Analysis

![Airplane](https://img.shields.io/badge/Airplane-Crashes%20Analysis-blue)
![License](https://img.shields.io/badge/License-MIT-green)

Overview

This repository dives into a comprehensive analysis of airplane crashes using a rich dataset. Explore trends, patterns, and gain insights into factors contributing to aviation incidents.

🚀 Motivation

Understanding the dynamics of airplane crashes is vital for enhancing aviation safety. This analysis aims to provide actionable insights and contribute to ongoing efforts in mitigating risks and improving overall safety measures.

📊 Analysis Queries

Unlock valuable insights with our carefully crafted SQL queries, covering diverse aspects such as fatalities over time, common aircraft manufacturers, distribution of fatalities by aircraft type, ground incidents, and more.


🚀 Usage

Utilize or adapt the provided SQL queries for your analyses or research. Contributions, suggestions, and improvements are highly welcomed. Feel free to open issues or create pull requests to share insights or enhancements.

📈 Queries Overview

### 1. Showing Databases:
This command lists all the available databases.
SHOW DATABASES;

### 2. Using the "airopalane" Database:
This command switches to the "airopalane" database for subsequent queries.
USE airoplane;

### 3. Displaying Contents of "aircrashes" Table:
This query retrieves all rows from the "aircrashes" table, displaying the complete dataset.
SELECT * FROM aircrashes;

4. Renaming Column in "aircrashes" Table:
This command renames the column with the name `ï»¿Year` to `Year` in the "aircrashes" table, resolving any encoding issues.
ALTER TABLE aircrashes
RENAME COLUMN `ï»¿Year` TO `Year`;


- Query 5 (Top 5 Fatalities Over Time):** Retrieves the top 5 years with the highest total fatalities in descending order.

- Query 6 (Most Common Aircraft Manufacturer):** Lists the top 4 most common aircraft manufacturers based on the crash count.

- Query 7 (Distribution of Fatalities by Aircraft Type):** Shows the top 5 aircraft types with the highest total fatalities.

- Query 8 (Ground Incidents Analysis):** Provides the total number of ground incidents each year.

- Query 9 (Operator-wise Fatality Rate):** Calculates the average fatality rate for each operator, ordered by rate in descending order.

- Query 10 (Yearly Evolution of Crashes):** Counts the total number of crashes for each year.

- Query 11 (Most Frequent Operator):** Identifies the operator involved in the most crashes.

- Query 12 (Top 5 Aircraft Models with Highest Fatalities):** Lists the top 5 aircraft models associated with the highest total fatalities.

- Query 13 (Quarterly Distribution of Crashes):** Provides the distribution of crashes by year and quarter.

- Query 14 (Crashes in World War I):** Retrieves all records of airplane crashes that occurred during World War I (1914-1918).

- Query 15 (Fatalities vs. Aboard Comparison):** Compares total fatalities to the total number of people aboard each year.

- Query 16 (Geographical Distribution of Crashes):** Displays the geographical distribution of crashes, indicating regions with the highest crash counts.

- Query 17 (Most Common Location for Crashes):** Lists the top 5 locations (cities or regions) with the highest crash counts.

- Query 18 (Monthly Ground Incidents Trend):** Shows the trend of ground incidents over the months.

- Query 19 (Operator-wise Ground Incident Rate):** Calculates the average ground incident rates for operators, ordered by the rate in descending order.

- Query 20 (Countries with Zero Crashes):** Identifies countries or regions with no recorded airplane crashes.

- Query 21 (Crashes Involving Zeppelins):** Counts the number of crashes involving zeppelins.

- Query 22 (Operators with the Highest Average Fatalities per Crash):** Lists the top 5 operators with the highest average fatalities per crash.

- Query 23 (Months with the Highest Percentage Increase in Crashes Year over Year):** Determines months with the highest percentage increase in crashes year over year.

- Query 24 (Countries with the Highest Ground Incident Rate):** Identifies countries or regions with the highest average ground incident rates.

- Query 25 (Average Fatalities per Quarter Over the Years):** Calculates the average fatalities per quarter over the years.

- Query 26 (Analysis of Crashes with Multiple Fatalities):** Provides the count of crashes with multiple fatalities for each year.

- Query 27 (Crashes with a High Number of Aboard but Low Fatalities):** Retrieves crashes with a high number of people aboard but low fatalities.

- Query 28 (Aircraft Models with the Highest Ground Incidents):** Lists the top 5 aircraft models with the highest total ground incidents.

- Query 29 (Operators with the Highest Ground Incident Rate):** Identifies the top 5 operators with the highest average ground incident rates.

- Query 30 (Aircraft Types with the Highest Average Fatalities per Ground Incident):** Lists the top 5 aircraft types with the highest average fatalities per ground incident.

- Query 31 (Distribution of Crashes by Aircraft Manufacturer and Year):** Provides the distribution of crashes by aircraft manufacturer and year.

- Query 32 (Months with the Highest Number of Ground Incidents):** Identifies the months with the highest number of ground incidents.


📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and adapt the code, respecting the terms outlined in the license.
