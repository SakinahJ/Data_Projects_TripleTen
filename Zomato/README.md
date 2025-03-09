# File Title: Zomato Restaurant Analysis

As a junior analyst at Zomato, this project focuses on evaluating restaurant performance using test datasets. The goal is to identify key factors contributing to restaurant popularity and revenue generation.

Key Analysis Areas:
Restaurant Popularity: Identifying top-performing restaurants based on customer engagement, ratings, and order frequency.
Revenue Drivers: Analyzing which restaurants generate the highest revenue and the factors influencing their success.
Insights & Recommendations: Exploring trends in cuisine type, location, pricing, and customer preferences to optimize business strategies.


<img src="https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Images/zomato.png" alt="First Sheet of Project**">

Project can be found <a href='https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Zomato/Zomato%20Presentation.pdf'><u>here</u>.</a>

Raw Data can be found <a href='URL HERE'><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Zomato Presentation](https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Zomato/Zomato%20Presentation.pdf) | PDF presentation of the Zomato Analysis |
| 2 | [RAW DATA FILE 1 HERE](https://docs.google.com/spreadsheets/d/12rtVvZ7dmY-wA6MhtOIX_RMqiYd849B8taoV-OwaUCo/edit?usp=sharing) | Raw file for the restaurant data used for analysis |
| 3 | [RAW DATA FILE 2 HERE](https://docs.google.com/spreadsheets/d/1sCyuRW6AeG6f6VFNQPLNVtkIouwSXh0fdjrCI-6Xjss/edit?usp=sharing) | Raw file for the menu data used for analysis |
| 4 | [CLEAN DATA FILE 1 HERE](https://docs.google.com/spreadsheets/d/12rtVvZ7dmY-wA6MhtOIX_RMqiYd849B8taoV-OwaUCo/edit?usp=sharing) | Raw file for the restaurant data used for analysis |
| 5 | [CLEAN DATA FILE 2 HERE](https://docs.google.com/spreadsheets/d/1sCyuRW6AeG6f6VFNQPLNVtkIouwSXh0fdjrCI-6Xjss/edit?usp=sharing) | Raw file for the menu data used for analysis |
| 6 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 7 | [Requirements.txt](https://docs.google.com/document/d/1jzZ7aFNw5tob83UqyLRSB6uvAA2uo_OjLuAOBe_4Qiw/edit?usp=sharing) | A simple .txt file with the provided project requirements as provided by TripleTen. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Process | Describes the process, including tools or tech used. |
| Data | Describes the data source, including files, tables, and fields. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |
| Recommendations | Recommended direction for the stakeholders based on final analysis. |
| Notes | List any special requests from the reviews or stakeholders unique to this project. |

#### Description:
- 8 worksheets in Power BI and 2 dashboards
- Restaurant Analysis: What restaurants are popular? What restaurants generate the highest revenue? Why?
- Includes KPI cards, pie charts, bar charts, and trend lines.
  
#### Process:
- Data Preparation – Cleaned and integrated multiple datasets to ensure accuracy and consistency.
- Exploratory Data Analysis (EDA) – Identified key trends in restaurant popularity, revenue, and customer engagement.
- KPI Development – Created key performance indicators (KPIs) to measure restaurant success and customer satisfaction.
- Visualization & Dashboard Creation – Designed interactive Power BI dashboards with charts, graphs, and tables for insights.
- Insights & Recommendations – Analyzed trends, identified revenue drivers, and provided data-driven recommendations for Zomato.

#### Data
DESCRIPTION HERE:Zomato data.zip
- `'Zomato data.zip'`: Compressed Excel files provided by team lead
    - `'orders'`: All orders made from the menu by all customers at all restaurants between Oct. 4th, 2017, and June 26th, 2020.
    - `'restaurant'`: All restaurants with ratings and location.

#### Assumptions:
- Restaurants with higher ratings and more reviews are generally more popular and profitable.
- Revenue is influenced by factors such as location, cuisine type, pricing, and customer engagement.
- Customer satisfaction is a key driver of repeat business and overall restaurant success.
- Restaurants with frequent orders and high customer retention generate more revenue.
- Delivery efficiency and service quality impact customer satisfaction and restaurant performance.
- Data provided is accurate, representative, and up-to-date for meaningful analysis.


#### Findings:
- Zomato has a large database of restaurant clients across cities in India.
- Sales have been declining since 2018.
- Indian cuisine is the most popular and generates the highest sales.
- American franchise restaurants receive more ratings than local restaurants, likely due to better marketing tools and a stronger online presence.
- Pizza is a popular cuisine, with Domino’s being the top-selling restaurant.
- The top cities generating the highest sales are Bangalore (Bengaluru), followed by Delhi, Mumbai, and Noida.

#### Recommendations/Results:
- Strategic Client Onboarding:
-- Focus on onboarding clients located in high-performing cities where our
platform demonstrates strong sales traction.
-Performance-Based Client Optimization: 
Conduct a thorough analysis to identify and potentially phase
out clients operating in low-performing areas.
-Evaluation:
Regularly evaluate clients with consistently low sales performance and consider potential
removal.
-Domino's Pizza:
The high sales generated by Domino's Pizza indicate a strong market demand for this
type of establishment. We should prioritize onboarding more Domino's Pizza locations in cities with
existing strong sales performance.
-Indian Restaurant Focus:
Indian cuisine is by far the most popular and has the highest sales. Given the
significant impact of reviews and ratings, I suggest prioritizing marketing efforts to enhance the online
presence and ratings of high-performing Indian restaurants, leveraging their potential for significant
growth.

#### Notes:
-Data: restaurant and orders tables were used for this analysis.
-Both tables were joined in Tableau using the r_id and id colums.
-Original data was in Indian ruppee currency, all currency was changed to reflect
USD.
-Both tables were all cleaned and outliers were filtered out.
-Data for 2020 only reflects half of the year.
-Cohorts were created for each year of sales and ratings in order to be able to filter
years and ratings during analysis.

