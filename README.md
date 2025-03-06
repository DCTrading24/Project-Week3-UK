UK Power Generation Analysis

Overview

This project analyzes the development of the power generation mix in the UK, with a focus on the role of renewables like wind and solar energy. The research is based on continuously updated data from the National Energy System Operator (NESO), spanning from 2009 to the present.

Objectives

Provide an overview of the UK's power generation mix by energy type.
Analyze the contribution of wind and solar energy to the overall generation mix and impact on power demand.

Data Source

The dataset is a CSV file continuously updated by NESO.
Data includes half-hourly energy generation records from 2009 to today.
Adjustments:
Correction of the "generation" column (excluding imports).
Introduction of a "demand" column to reflect actual power needs.

Key Findings

1. Development of the Generation Mix
Coal phase-out is evident in recent years.
Wind energy generation has increased significantly.
Imports have risen to compensate for fluctuations in supply.
Gas and wind are the dominant sources in the UK’s energy mix.

2. Energy Demand Trends
Peak demand occurs during morning and evening hours on weekdays.
Monday ramp-up is slow, and Fridays see an earlier demand drop.
Weekends have the lowest demand.

3. Impact of Renewables
Higher demand in winter increases reliance on traditional power sources.
Net demand is defined as total demand minus wind and solar generation.
Renewables significantly reduce the need for conventional power plants and imports.
Lowest net demand occurs in October.

4. Wind & Solar Energy Availability
Weak positive correlation (+56%) on a daily basis.
Strong negative correlation (-96%) on a monthly basis, meaning wind and solar tend to compensate for each other over longer periods.

5. Statistical Insights on Wind and Solar Generation
Wind Power

Maximum generation: 22,510 MW
Minimum generation: 1 MW
Mean generation: 4,830 MW (27.3% share)
Median generation: 25.4%
Skew: 0.31 (slightly right-skewed)
Kurtosis: -0.96 (low probability of extreme outliers)

Solar Power

Maximum generation: 11,498 MW
Minimum generation: 0 MW
Mean generation: 862 MW (3.95% share)
Median generation: 0% (high variability)
Skew: 1.66 (right-skewed, meaning occasional high peaks)
Kurtosis: 1.9 (prone to extreme values)
