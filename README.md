# ForEVs -- Forecasting the market potential for Electric Vehicles (EVs)
The importance of using sustainable lifestyle methods that preserve the natural resources and climate of the Earth cannot be over-stressed. 
This includes trying to manage the global carbon-emission footprint by finding alternative means of fuel for our vehicles. 
This project focuses on using Electric Vehicle (EV) and Charging Station Data from the EValuateNY database on the [NYSERDA](https://www.nyserda.ny.gov/all-programs/programs/chargeny/support-electric/data-on-electric-vehicles-and-charging-stations) website. 
This resource contains a rich dataset that combines EV market information (registration and charging statistics) with demographic and location-based information for the state of New York. 
The primary motivation for this project is to explore the dataset to find correlations among key parameters that influence the EV market.
The goal of the project is to develop a forecasting tool, using statistical techniques and Machine learning models, that will inform the strategies used by EV Provider networks and government policy makers to maximize EV deployment in communities.

## Datasets
### Registrations
* `VIN`
* `Vehicle Names`
* `ZIP Codes`
* `Registration Type`
* `Start and Expiration Date`

### Charging Station Usage
* `Start Dates`
* `ZIP Codes`
* `Energy Usage`
* `Active Stations`
* `Active Ports`

### Demographics
* `ZIP Codes`
* `Household income`
* `House Ownership`
* `Number of people with given Education Level`
* `Time to commute to work`

### Rebate Information
* `ZIP Codes`
* `Annual Greenhouse Gas Emissions`
* `Annual Petroleum Reduction`
* `Rebate`

# Project Goals
* Find the most important factors affecting the EV market
* Train a ML model for each regional database based on these factors and assess performance
* Deploy as an end to end Python package

## Exploratory Plots
### Cumulative Registrations
![](https://github.com/sidmohite/tdi_capstone_project/blob/main/plots/cumulative_regs_time.png)

### Monthly Registrations
![](https://github.com/sidmohite/tdi_capstone_project/blob/main/plots/monthly_regs_time.png)

### Active Charging Stations
![](https://github.com/sidmohite/tdi_capstone_project/blob/main/plots/charging_stations_time.png)

### EV Correlations with Demographics
![](https://github.com/sidmohite/tdi_capstone_project/blob/main/plots/EV_Charge_vs_Education.png)

#### Global phenomena such as COVID-19 Pandemics can influence the market ...
![](https://github.com/sidmohite/tdi_capstone_project/blob/main/plots/Energy_time_series.png)
