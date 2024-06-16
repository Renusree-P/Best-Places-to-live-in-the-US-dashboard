# Best-Places-to-live-in-the-US-dashboard
#### Table of contents
- [Overview](#overview)
- [Objectives](#objectives)
   - [Data Integration](#data-integration)
   - [Interactive Analysis](#interactive-analysis)
   - [User-Friendly Interface](#user-friendly-interface)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Limitations](#limitations)
- [Future Work](#future-work)
  
#### Overview
The "Best Places to live in the US" project is a dashboard which acts as an analytical tool to evaluate and compare various cities in the United States based on different criteria according to the user. This project aim is to help users make decisions about which place to select based on Purchasing power Index, Health care index, Cost of Living index, Rent index, temperature, Crime rate, Tax rate, Air Quality index.

#### Objectives
- #### Data Integration
   Combine various datasources to create a single comprehensive dataset that has different factors influencing the users decision to choose a city for living.
- #### Interactive Analysis
   Develop an interactive dashboard that allows the user to identify the factors according to their prefernce and allocate weights to different factors as per their preference.
- #### User-friendly Interface
   The dashboard must be easily understandable and accessible to any novice user and provode a seamless experience.

#### Data Sources
The datasets were collected from various sources like United States Environmental Protection Agency, Numbeo, Statista.com, currentresults.com
- Traffic dataset - [Download](https://www.numbeo.com/traffic/country_result.jsp?country=United+States)
- Health care dataset - [Download](https://www.numbeo.com/health-care/country_result.jsp?country=United+States)
- Air Quality dataset - [Download](https://aqs.epa.gov/aqsweb/airdata/download_files.html#Daily)
- Income dataset - [Download](https://www.statista.com/statistics/205609/median-household-income-in-the-top-20-most-populated-cities-in-the-us/)
- Quality of life dataset - [Download](https://www.numbeo.com/quality-of-life/country_result.jsp?country=United+States)
- Cost of living dataset - [Download](https://www.numbeo.com/cost-of-living/region_rankings_current.jsp?region=019)
- Crime rate dataset - [Download](https://www.kaggle.com/datasets/kabhishm/united-states-crime-rates-by-city-population)
- Temperature dataset - [Download](https://www.currentresults.com/Weather/US/average-annual-state-temperatures.php)
  
#### Methodology
- This project uses data processing techniques to  clean the data and normalize the data.
- The dashboard is made using Excel
- The dashboard is constructed using various functionalities of excel like XLOOKUPs, Macros, Slicer, Excel charts, conditional formatting, Pivot tables, Power Query, Power pivot, 3D Maps.
- This dashboard is built to facilitate interactive and dynamic visualization.

#### Limitations
- Real-time data: The datasets used for this dashboard project belong to a specific year. The data is not real-time. So, if the dashboard is to be used for a different year, again the datasets of the required year are to be sourced and prepreocessed again.
- Scope: This dashboard considers only the factors for which the data is avaliable. So the effect of remaining important qualitative factors is not captured.
  
#### Future Work
- Expanded inclusion of factors: Additional important factors like education quality, precipitation etc are to be incorporated.
- Real time data integration - Real-time data integration can be done to keep the dashboard updated.
- User feedback - There must be a mechanism to gather timely user feedback and make the nescessary improvements.
  
