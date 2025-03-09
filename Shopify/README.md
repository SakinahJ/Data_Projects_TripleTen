

# File Title: Shopify App Analysis

This independent project, part of the TripleTen Business Intelligence Analytics Program, highlights my skills in Power BI.

Objective:
Analyze data from publicly available Shopify websites to identify key factors contributing to the success of Shopify apps.

<img src="https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Images/sprint%206%20project.png" alt="First Sheet of Project**">

Project can be found <a href='URL HERE’><u>here</u>.</a>
Raw Data can be found <a href='URL HERE'><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://docs.google.com/document/d/1zI3M7jNENdJgVd2Lg2QNkEok7WJjzpmKeq9dtXpqcxM/edit?usp=sharing) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 3 | [Project Summary](https://docs.google.com/document/d/1wOvwgkWLI1fbcOORLJhPYhIHTW3wh4LLxVCw7NOG278/edit?usp=sharing) | A .txt file with Data Model, DAX Calculated Fields, and Dashboards.|

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
- 3 page Power BI Dashboard
- Includes data analysis, KPI cards and Charts

#### Process:
1.Assessed App Store Landscape – Used KPI cards and charts to analyze key metrics.
2.Cataloged Review Data – Visualized review trends with cards and charts.
3.Analyzed App Developers – Examined developer performance across different review types.

#### Data
DESCRIPTION HERE: The Excel file provided by TripleTen was was public data scraped from the Shopify App Store.
- `'shopify.xlsx'`: Excel Workbook containing 4 sheets
    - `'apps'`: Details of the apps on the Shopify apps marketplace
    - `'apps_categories'`: Join tables to connect apps with categories
    - `'categories'`: Categories of the apps. Each app has multiple categories
    - `'reviews'`: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

#### Assumptions:
- The scraped data from Shopify websites is accurate and representative of the actual app landscape.
- The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
- The provided column names and data types in the tables accurately reflect their content.


#### Findings:
- New apps tend to receive ratings early in their deployment.
- Most apps receive favorable ratings.
- Developer responses to reviews positively impact overall ratings.
- Reviews marked as helpful have an average rating of 5.48.
- Top Developers:
- Elfsight holds the highest total rating at 135.10 stars.
- Pictorem has the highest average helpful reviews at 50.
- FireApps leads in review engagement with 6,008 responses.


