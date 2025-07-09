# Database-Concepts-Project

The project aims to develop a relational database that manages and analyzes meteorological data at the county level across weather stations in the southeastern U.S, specifically Florida, Georgia and South Carolina. The primary goal is to provide a structured database for storing and analyzing the key meteorological variables of air temperature, precipitation, and air pressure. 
 
The database focuses on capturing data from distinct weather stations and will provide insights into extreme weather events and trends, by enabling efficient querying and analysis through SQL. The goals of the project are: 
1.	Use SQL to elicit information from the database that will allow users to retrieve information about extreme weather events. For example, using an INNER JOIN to find periods where the temperature exceeded a certain threshold, using the Temperature and Station tables. 
 
2.	Analyzing trends: The database will include historical data over multiple years. Therefore, daily meteorological data can be aggregated into monthly averages using SQL, allowing for the analysis of trends in average precipitation and temperature values across different regions. 
 
3.	Normalization: The database will be designed using normalization techniques to reduce redundancy. For example, by separating the temperature, precipitation, and air pressure values into separate tables, update anomalies are prevented. If you store all weather data (temperature, precipitation, and air pressure) in a single table, when you want to insert a new reading for temperature for example, you would have to insert all the other related values (precipitation, air pressure), even if they are not available. 
 
Also, if all weather data is stored in a single table, deleting a record for one type of weather data (e.g., temperature) could cause you to delete all related weather data. 
 


## Technology Used
- Sequel Ace


