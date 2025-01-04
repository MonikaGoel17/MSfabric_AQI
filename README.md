# Microsoft_Fabric_Data_Engineering_Project_AQI

**Project Title: Air Quality Index (AQI) Monitoring for Capital Cities Worldwide**

This project focuses on developing a robust data engineering and visualization pipeline to monitor and analyze air quality in capital cities worldwide. By leveraging Microsoft Fabric, PySpark notebooks, and Power BI, the solution automates the collection of Air Quality Index (AQI) data from public API, processes it, and presents it in a user-friendly manner. 


**Data Engineering**

**1.	Data Preparation and Loading:**

•	As a first step, coordinates (latitude and longitude) for capital cities across the globe were sourced from publicly available data on the internet in the form of a CSV file.

•	The CSV file was then uploaded into a Microsoft Fabric Lakehouse environment using a PySpark notebook. This process converted the raw data into a structured table format, enabling easier access and manipulation for downstream tasks.

**2.	Air Quality Data Collection:**

•	To gather Air Quality Index (AQI) data for the capital cities, the World Air Quality Index (WAQI) API was integrated into the project. The API required longitude and latitude values for each city as input to retrieve accurate air quality data.

•	Using PySpark notebooks, the AQI data was fetched for all capital cities and subsequently stored in a separate table in the Lakehouse.

•	A data pipeline was built to automate the AQI data extraction process. This pipeline is configured to run every night, ensuring the Lakehouse is continuously updated with the latest air quality information. This automated workflow guarantees the availability of up-to-date data for visualization and analysis.

**Data Visualization**

•	A comprehensive Power BI report was created to visualize and analyze the AQI data stored in the Lakehouse.

•	The report features intuitive dashboards that display key insights, such as comparative AQI levels across cities and highlights of cities with the best and worst air quality.




