HERITAGE TREASURES: AN IN-DEPTH ANALYSIS OF UNESCO WORLD HERITAGE SITES USING TABLEAU
 1. Introduction
UNESCO World Heritage Sites represent locations of outstanding cultural or natural importance to humanity. These sites are protected and preserved due to their historical, environmental, and social significance. However, understanding global heritage distribution and identifying endangered sites from raw datasets is difficult.
This project uses Tableau to transform UNESCO World Heritage data into an interactive visual dashboard. The analysis focuses on site distribution, endangered heritage locations, and regional inscription trends from 1978 to 2019.
The aim of the project is to provide a clear understanding of global heritage patterns using data visualization techniques.
 
 2. Objectives
The main objectives of this project are:
* To analyze the distribution of heritage sites across countries
* To identify sites that are categorized as endangered
* To study the growth of heritage site inscriptions over time
* To create an interactive dashboard using Tableau
* To present insights in an easy-to-understand visual format

3. Tools and Technologies Used
* Tableau Public / Tableau Desktop
* Data Visualization Techniques
* Data Cleaning and Aggregation
* Microsoft Excel (for dataset handling)

4. Dataset Description
The dataset used in this project contains information about UNESCO World Heritage Sites. Each record represents a heritage property.
The dataset includes the following attributes:
* Name of the Site (Name En)
* Country
* Region
* Year of Inscription (Date Inscribed)
* Danger Status (In Danger / Not in Danger)
* Category of the Site

The data ranges from 1978 to 2019 and includes more than 1000 heritage locations worldwide.

 5. Methodology
Step 1: Data Preparation
The dataset was downloaded and imported into Tableau. Data types were corrected (date fields converted to date format), and calculated fields were created to categorize danger status properly.
Step 2: Data Visualization

Three main visualizations were created:

1. Treemap
2. Pie Chart
3. Line Chart
Step 3: Dashboard Design

All visualizations were combined into a single interactive dashboard. Filters and actions were applied to allow users to explore the data dynamically.

 6. Visualizations

 6.1 Heritage Sites by Country (Treemap)
A treemap visualization was used to represent the number of heritage sites per country. Each block represents a country and the size of the block corresponds to the number of heritage sites.
This helps identify countries with the highest concentration of world heritage properties.

6.2 Heritage Sites at Risk (Pie Chart)
A pie chart was created to show the proportion of sites classified as “In Danger” and “Not in Danger”.
This visualization helps understand the level of threat faced by global heritage locations and highlights the need for conservation.

6.3 Regional Inscription Trends (Line Chart)
A line chart was created to analyze how many heritage sites were added each year from 1978 to 2019.
The chart is segmented by region, allowing comparison between different parts of the world and identifying periods of increased heritage recognition.

 7. Dashboard Features
The dashboard includes:
* Interactive filtering
* Region-wise comparison
* Year-wise trends
* Country-level distribution

Users can click on a country or category and the other charts update automatically.

8. Key Insights
* Europe and North America contain the largest number of heritage sites.
* Only a small percentage of sites are classified as endangered.
* The number of heritage inscriptions increased significantly after the 1990s.
* Some regions show rapid growth in heritage recognition compared to others.

9. Conclusion
This project demonstrates the importance of data visualization in understanding global heritage conservation patterns. By using Tableau, complex historical data was transformed into meaningful insights.
The dashboard allows users to explore heritage data interactively and helps highlight regions and sites that require attention and preservation.

10. Future Enhancements
Future improvements may include:
* Adding geographic map visualization
* Predicting future heritage site growth
* Including recent datasets beyond 2019
* Advanced analytics using forecasting models

 11. References
* UNESCO World Heritage Centre
* Kaggle Dataset: UNESCO World Heritage Sites
* Tableau Official Documentation
