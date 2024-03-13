# Restaurant Sales Forecasting
Predicting future sales for three Uppsala-based restaurants using historical data.

## Data
- Sales data obtained from [Caspeco](https://www.caspeco.se/)
- Covid-19 data sourced from [Socialstyrelsen](https://www.socialstyrelsen.se/statistik-och-data/statistik/statistik-om-covid-19/)
- Temperature data acquired from [SMHI](https://www.smhi.se/data/meteorologi/ladda-ner-meteorologiska-observationer#param=airtemperatureInstant,stations=core)
- Holiday information retrieved from [Nager](https://date.nager.at/Api)

## Features
#### Raw
- Time (Year, Month, Week, Weekday, Day)
- Holiday
- Temperature
- Number of Covid-19 ICU Patients

#### Engineered
- Weekend (Friday/Saturday)
- Sales Lagged by 7 Days (LAG7)
- 2-Day Moving Average of Sales Lagged by 1 Day (MA2)
