### Data Engineering Challenge 1

Complete challenge using:
1. Python Data Science Toolset
2. Online drawing tool (https://draw.io)
3. Dataset provided at top level of this repository.

#### Scenario

Fleet Operations needs an asset monitoring system for the wind turbine fleet they support. The team would like to consume key metrics from a web dashboard with daily, weekly, monthly, and yearly resolutions of key metrics (Availability, Reliability etc.)

The system must have the ability to:
- Collect timeseries data from wind turbines (based on dataset provided)
- Support demographic information (Site Name, Wind Turbine Name, Wind Turbine ID, Wind Turbine Model, Location etc.)
- Provide metrics Computation (with the ability to add additional metrics)
- Do quality Checks
- Do system and Data Monitoring
- Support job Scheduling
- Visualize information (metrics and raw data)

#### Challenges

1. Draw a diagram of the system. Note technologies selected (e.g. Database type/name, infrastructure etc.)

2. Create a diagram that shows the entities and relationships between data sets in the system.

3. Write out the SQL statement to create the timeseries entity (include only 5 columns) in a database.

4. Create a script to extract `DateTime` plus select columns of timeseries data provided, then save to Parquet.

5. Using the provided dataset, create a script that displays the max `Ws_avg` grouped by turbine and includes the `Wind_turbine_long_name` in addition to `Wind_turbine_name` in the table.

6. Provide a script that can visualize `Ws_avg` for turbine `R80711` as a line graph. On the graph, add a horizontal line to indicate the 10 meters per second threshold.



