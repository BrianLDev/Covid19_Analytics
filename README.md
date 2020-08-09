# Covid-19 (Coronavirus) Analytics

## Files:
### Jupyter Lab Analytics:
- **[Covid-19 (Coronavirus) Analytics and Forecasting (Jupyter Notebook)](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Analytics.ipynb)**
- [Extract, Transform, Load (ETL) Data preparation notebook for Covid-19 datasets](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Data_ETL.ipynb)
### Datasets
- [John Hopkins University Datasets](https://github.com/BrianLeip/Covid19_Analytics/tree/master/Datasets/JH)
- [Covid Tracking Project Datasets](https://github.com/BrianLeip/Covid19_Analytics/tree/master/Datasets/CT/)

## Data Sources

### Primary Data Source: Johns Hopkins CSSE Data Repository 
- Link: https://github.com/CSSEGISandData/COVID-19  
- **Live data:**
    - Countries (cases, deaths, recoveries, active)
    - US States (cases, deaths)
    - US County (cases, deaths)
- **Historic time series data:**
    - Countries (cases, deaths, recoveries, active)
    - US States (cases, deaths)
    - US Counties (cases, deaths)

### US State Testing and Hospitalizations: Covid Tracking Project 
- Link: https://covidtracking.com/data/ 
- **Live data:**
    - US State testing and hopspitalization, ICU stats
- **Historic time series data:**
    - US State testing and hopspitalization, ICU stats

## Methodology:
- Data is first gathered from various sources and then transformed into formats more conducive to EDA, analytics, and data viz with Python and various libraries like Pandas and Matplotlib
- All original data remains unchanged, only rearranged in a more usable format or summarized (e.g. Confirmed Cases subtotal by Country OR Deaths subtotal by US State)
- Reformatted files are exported daily at end of day to the [Datasets](https://github.com/BrianLeip/CoronaVirus/tree/master/Datasets) folder, within each data source's respective folder.
- Data is then loaded into the Covid19_Analytics notebook for EDA, analytics, and forecasting
- See the [Covid19_Data_ETL file](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Data_ETL.ipynb) for the full Extract, Transform, Load process and logic

