# ⚡ Harry Potter Franchise: Insights & Analytics

An interactive Power BI dashboard exploring the Harry Potter movie franchise across all 8 films. The report provides insights into financial performance, character dialogue distribution, spell usage, and key filming locations.

<img width="1321" height="740" alt="HP analysis" src="https://github.com/user-attachments/assets/e5f31cbc-8df7-468e-901a-d45cb182dd99" />

## Business Questions
* How did production budgets and box office revenues evolve from the first film to the finale?
* Which characters have the most lines, and how does their dialogue share shift across the series?
* Which spells and filming locations appear most frequently throughout the franchise?

## Key Insights
* **Financial Growth:** Production budgets doubled from **$125.0M** (*HP 1*) to **$250.0M** (*HP 8*), while box office revenue peaked in the final film at **$1,342.0M**.
* **Dialogue Distribution:** *HP 6* features the highest total number of dialogues (**830**), whereas *HP 4* has the fewest (**450**). Harry Potter leads in lines across every film, followed by Hermione Granger and Ron Weasley.
* **Top Spells:** *Expecto Patronum* and *Expelliarmus* share the top spot as the most frequently used spells (**13.2%** each among the top 10).
* **Key Locations:** *The Great Hall* is the most active location across the series (**557** total occurrences), followed by *4 Privet Drive* (**347**) and the *Gryffindor Common Room* (**343**).

## Dashboard Overview
* **Financial Performance by Movie:** Area/line comparison of Box Office revenue vs. Budget across all 8 movies.
* **Total Dialogues per Movie:** Bar chart tracking overall dialogue volume per installment.
* **Dialogues of Main Characters:** Line chart comparing spoken lines for Harry Potter, Hermione Granger, and Ron Weasley.
* **Top 10 Most Used Spells:** Donut chart showing the share of the most frequently cast spells.
* **Key Locations Dynamics:** Matrix heatmap highlighting scene/dialogue activity across iconic locations by movie.
* **Interactive Slicers:** Filter the entire report dynamically by *Character Name*, *Release Year*, *Hogwarts House*, and *Gender*.

## Data & Preparation
* **Source:** Harry Potter Movies Dataset (Maven Analytics).
* **Data Cleaning (Power Query):** Removed currency symbols (`$`) from financial columns to convert text strings into numeric formats, filtered out empty/null values, standardized column names, and verified data types.
* **Data Modeling:** Configured one-to-many relationships between lookup tables (characters, movies, locations) and fact tables.

## Tools & Skills Used
* **Power BI Desktop** (Data Modeling, Interactive Visualizations, Custom Theme & Visual Hierarchy)
* **Power Query** (Data Cleaning & Transformation)
* **DAX** (Calculated Measures & Aggregations)
