


# Predictive Maintenance Optimization with Prophet and Python
### This project leverages Facebook Prophet and Python to forecast maintenance needs and optimize scheduling for critical machinery. By using advanced time series forecasting techniques, we aim to minimize downtime, optimize resource allocation, and prioritize critical jobs effectively.




## Problem Statement
#### Maintenance scheduling for machinery often involves reactive measures, resulting in unplanned downtimes and inefficiencies. This project addresses these challenges by:
Forecasting Workload: Using historical workload data to predict future maintenance needs.
Identifying Critical Jobs: Flagging high-priority jobs with significant workload or operational importance.
Batching Maintenance: Grouping maintenance tasks into optimal intervals to reduce downtime and costs.


## Presentation
#### The accompanying slide deck explains the problem, methodology, and actionable insights derived from this project. It includes:


![image](https://github.com/user-attachments/assets/4adafcd0-4aee-486b-90da-cb760eaa656d)


### Problem Overview
#### Methodology (Prophet Modeling & Batching Logic)
#### Key Insights
#### Recommendations - PowerBi Dashboard



## Features
#### Time Series Forecasting:
#### Predict workloads using Prophet’s yhat values.
#### Simulate workload changes under planned maintenance scenarios (yhat_planned).

#### Maintenance Prioritization:
Flag critical jobs based on workload thresholds
Identify jobs needing maintenance using customizable ratios.


![image](https://github.com/user-attachments/assets/163be33c-a338-4518-a155-a9c9854e0abc)




#### Batch Scheduling:
Group maintenance tasks into 7-day rolling windows.
Optimize batch jobs to reduce operational disruption.

#### Visualizations:
Interactive graphs showing forecasted workloads, planned workloads, and critical/maintenance-needed markers.
Overlayed bar charts for quick comparison of actual vs. planned workloads.
