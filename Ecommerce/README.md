🚧 PROJECT PAGE UNDER CONSTRUCTION 🚧

# Ride-Sharing Data Analysis for Zuber

This project focuses on analyzing ride-sharing data to uncover patterns in passenger preferences and the impact of external factors, such as weather, on ride frequency. As an analyst for Zuber, a new ride-sharing company in Chicago, I studied the company’s database and competitor data using SQL to identify trends, optimize services, and understand market dynamics.


[<img src="https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Images/SQL%20Ecommerce1.png" alt="First Sheet of Project**">]

Video Overview can be found <a href='URL HERE’><u>here</u>.</a>
Project can be found <a href='URL HERE’><u>here</u>.</a>
Raw Data can be found <a href='URL HERE'><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Zuber Tasks and Results](https://docs.google.com/document/d/18yeuLe5ncimN3pTB99yw3jiHhuXYfKfJDhuY_dBeS84/edit?usp=sharing) | Each task and its result  |
| 2 | [RAW DATA FILE HERE](https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Images/tablescheme.png) | Image of the data and the relationships within the data |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/SakinahJ/Data_Projects_TripleTen/blob/main/Ecommerce/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

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
- 6 step SQL Query
- Exploratory data analysis and investigation of whether the duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.

#### Process:
Analyzed taxi rides by the company for specific dates, sorting by trip count.
Analyzed rides for companies containing specific keywords, grouping by company name.
Retrieved neighborhood IDs for O'Hare and Loop.
Categorized weather conditions by hour.
Retrieved Saturday rides from Loop to O'Hare, including weather and duration.
Sorted the results.

#### Data
A database with info on taxi rides in Chicago provided by TripleTen:

'neighborhoods' table: data on city neighborhoods

'name': name of the neighborhood

'neighborhood_id': neighborhood code

'cabs' table: data on taxis

'cab_id': vehicle code
'vehicle_id': the vehicle's technical ID
'company_name': the company that owns the vehicle
'trips' table: data on rides
'trip_id': ride code
'cab_id': code of the vehicle operating the ride
'start_ts': date and time of the beginning of the ride (time rounded to the hour)
'end_ts': date and time of the end of the ride (time rounded to the hour)
'duration_seconds': ride duration in seconds
'distance_miles': ride distance in miles
'pickup_location_id': pickup neighborhood code
'dropoff_location_id': dropoff neighborhood code
'weather_records' table: data on weather
'record_id': weather record code
'ts': record date and time (time rounded to the hour)
'temperature': temperature when the record was taken
'description': a brief description of weather conditions, e.g. "light rain" or "scattered clouds"

#### Assumptions:
The trips table and weather_records table do not have a direct relationship in the database.
The neighborhood_id serves as the primary key for the neighborhoods table.
The cab_id serves as the primary key for the cabs table.
The trip_id serves as the primary key for the trips table.
The record_id serves as the primary key for the weather_records table.


#### Findings:
Flash Cab recorded the highest number of taxi rides on November 15th-16th, 2017, with a total of 19,558 trips.
When filtering for taxi companies containing the keyword "Yellow" or "Blue", Blue Diamond had the highest number of rides between November 1st-7th, 2017, totaling 6,764 trips.
A comparison of the two most popular taxi companies, Flash Cab and Taxi Affiliation Services, against all other available companies for November 1st-7th, 2017, revealed that the total number of rides from "Other" companies was significantly higher than each top company individually or even when combined.
The SQL neighborhood_id values for the O’Hare and Loop neighborhoods are 63 and 50, respectively.
Each hour in the dataset was assigned a designated weather condition, starting with a default classification of "Good."
A SQL table was generated to display all taxi rides that began in the Loop on a Saturday and ended at O’Hare. The table included start time, weather conditions, and trip duration.

#### Recommendations/Results:
Based on the analysis of ride-sharing and taxi trends, the following recommendations can help Zuber optimize its services and improve market positioning:

Target Peak Demand Periods – Since Flash Cab had the highest number of rides on Nov. 15-16, 2017, Zuber should analyze similar peak demand trends and increase driver availability during those periods to maximize ride fulfillment.

Focus on High-Demand Neighborhoods – With O’Hare (ID #63) and Loop (ID #50) being key ride locations, Zuber should consider promotional pricing, driver incentives, or marketing efforts in these areas to attract more passengers.

Weather-Based Surge Pricing & Availability – Since each hour is assigned a weather condition, Zuber can implement dynamic pricing or increase ride availability during adverse weather conditions when demand may be higher.

Competitor Strategy Analysis – Given that "Other" companies had a higher total ride count than Flash Cab and Taxi Affiliation Services combined, Zuber should study these competitors to understand their pricing, service quality, or availability strategies and adjust accordingly.

Branding & Marketing Strategies – Since companies like "Blue Diamond" had high trip volumes within a specific date range, Zuber could leverage branding techniques like targeted promotions or strategic partnerships to compete with well-established taxi brands.

Optimize Routes & Reduce Wait Times – By analyzing rides starting in the Loop and ending at O’Hare, Zuber can optimize driver dispatching and route efficiency to minimize passenger wait times and enhance customer satisfaction.


