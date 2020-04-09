# Covid-19 (Coronavirus) Analytics and Forecasting
***
*WORK IN PROGRESS*
***

## [CoronaVirus Analytics and Forecasting (Jupyter Notebook)](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Analytics.ipynb)

### Data Sources:

- **Primary Data Source:** Johns Hopkins CSSE Data Repository - https://github.com/CSSEGISandData/COVID-19  
    - Live data:
        - Countries
        - US States
        - US County
    - Historic data:
        - Countries (cases, deaths, recoveries)
        - US States (cases, deaths) **PENDING**
        - US Counties (cases, deaths) **PENDING**
- **US State Testing and Hospitalizations:** Covid Tracking Project - https://covidtracking.com/data/  
    - Live data:
        - US State testing and hopspitalization, ICU stats
    - Historic data:
        - US State testing and hopspitalization, ICU stats
- **US County - Alternative:** NY Times - https://github.com/nytimes/covid-19-data/
    - Historic data:
        - US States (cases, deaths)
        - US Counties (cases, deaths)  

### Methodology:
- Data is first gathered from various sources and then 'wrangled' into formats preferable for EDA, analytics, and data viz
    - *No data was changed, only rearranged*
- Reformatted files are then exported to the `Datasets` folder and later loaded into the Covid19_Analytics notebook
- See the Covid19_Data_ETL file for the full Extract, Transform, Load process and logic

---
In addition to the Coronavirus Analytics Jupyter Notebook, I also did some simple forecasting in Excel on 3/15/2020 to predict the number of confirmed cases and estimated date when the US would go on full lockdown.  

**[US Confirmed Cases Forecasting from 2020-03-15 (Excel)](https://github.com/BrianLeip/CoronaVirus/blob/master/CoronaVirus%20US%20Lockdown%20Forecast%20(Excel).xlsx)**


 