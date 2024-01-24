# Jersey City Citi Bike Analysis for 2023
<img src="assets/kisspng-logo-citi-bike-new-york-city-citibank-product-claim-a-free-24-hour-citi-bike-nyc-day-pass-today-5bac83472c0409.6950069515380324551803.png">

## Description
The data found in the 2023 Citi Bike Trip History Logs for Jersey City was initially aggregated using SQLite csv file batch importing capabilities. Initial exploration and data cleanup was done in SQLite and then exported as a single csv file. Additional data cleanup was conducted using pandas library in Jupyter Notebooks. 

The final cleaned data was imported in Tableau. The Tableau dashboard can be found [here](https://public.tableau.com/app/profile/jacob.dolinsky/viz/citibiketrips_17060358922340/Dashboard1)

## Analysis

TThe total number of trips in 2023 was around 985.5K. The monthly average number of trips in 2023 was 82K. The months with above average numbers  of trips were April through October, which usually are the months with warmer weather. Average trip duration was 10.6 minutes.

There was no major difference in trip duration based on time of year. The majority of trips were conducted using classic bikes.

The majority of trips were completed by members. On average 26% of casual users rented bikes in 2023. The highest monthly percentage of casual users was 31% in July.

Top five start stations:
- Grove St PATH - 5%
- Hoboken Terminal - River St & Hudson Pl - 4%
- Hoboken Terminal - Hudson St & Hudson Pl - 3%
- South Waterfront Walkway - Sinatra Dr & 1 St - 3%
- City Hall - Washington St & 1 St - 2%

The first three stations are in direct proximity to PATH which is a vital connection between New York and New Jersey. The other two are located in major congregation areas. 

## Data

Data was provided by the Citi Bike program. [Citi Bike Data](https://citibikenyc.com/system-data)

## Technology 

SQLite, Python, Tableau.