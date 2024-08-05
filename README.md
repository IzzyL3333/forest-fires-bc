# :fire: 📉 Linear Correlation Analysis on BC Forest Fires
The team was responsible for creating a scientific report based on climate or related measurements that demonstrate environmental changes due to human impact. 
To evaluate an aspect of the climate emergency using time series and data analysis tools. This project was to display the scientific process through a formal presentation. 
The topic chosen was the following: A Linear Correlational Analysis of the Influence of Anthropogenic-caused Fires, Yearly Atmospheric Carbon Dioxide Levels, Canada’s Carbon Dioxide Emission Levels, 
and Prince George’s Precipitation Levels on the Yearly Hectares Burned by Forest Fires in British Columbia from 1990 to 2021. 
The project discussed whether various types of fire-related data are positively correlated to each other.
## Table of Contents
[Project Questions](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#project-questions)

[Project Methodology & Datasets](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#project-methodology--datasets)

[Preliminary Data Analysis](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#preliminary-data-analysis)
- [Total Number of Fires from Human Activity in BC from 1990 to 2021](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#total-number-of-fires-from-human-activity-in-bc-from-1990-to-2021)
- [Total Number of Fires in BC from 1990 to 2021](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#total-number-of-fires-in-bc-from-1990-to-2021)
- [Total Area Burned in Hectares in BC from 1990 to 2021](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#total-area-burned-in-hectares-in-bc-from-1990-to-2021)

[Climate Change Analysis]()
  - [Area Burned vs. Human Activity Fires in BC (1990-2020)](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#area-burned-vs-human-activity-fires-in-bc-1990-2020)
  - [Atmospheric CO<sub>2</sub> vs Area Burned in BC (1990-2021)](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#atmospheric-co2-vs-area-burned-in-bc-1990-2021)
  - [Area Burned in BC vs. Canada Fossil CO<sub>2</sub> Emissions (tons) (1990-2016)](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#area-burned-in-bc-vs-canada-fossil-co2-emissions-tons-1990-2016)
  - [Annual Precipitation (mm) vs Area Burned (ha) in BC (1990-2021)](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#annual-precipitation-mm-vs-area-burned-ha-in-bc-1990-2021)

[Summary of Results](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#summary-of-results)

[Discussion](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#discussion)

[Conclusion](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#conclusion)

[Bibliography](https://github.com/IzzyL3333/forest-fires-bc/new/main?filename=README.md#bibliography)
## Project Questions
1. Is the number of yearly human-caused fires across British Columbia, reported by the National Forestry Database, significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2020?
2. Is the yearly atmospheric carbon dioxide levels at Mauna Loa station significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2021?
3. Is Canada’s yearly carbon dioxide emission levels calculated by the Emission Database for Global Atmospheric Research​​ from fossil fuels significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2016?
4. Is the average yearly precipitation recorded at the Prince George weather station significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2021?

**NOTE: the reason for the different ranges of years between project questions came from limited data availability.**
## Project Methodology & Datasets
Our data collection came from the National Forestry Database and Emission Database for Global Atmospheric Research​​. 
Our CO<sub>2</sub> data was used from Mauna Loa as their levels were consistent with BC. We used Prince George's precipitation levels because they are less affected by coastal weather patterns. 

Starting the preliminary data analysis, we plotted the following raw data as a time series and conducted a linear regression on each to observe any potential trends over time. 
- Total Number of Fires from Human Activity in BC from 1990 to 2021
  - Filename: “HumanActivityFires.csv” 
- Total Area Burned in Hectares in BC from 1990 to 2021
  - Filename: “AreaBurnedOverall.csv”
- Total Number of Fires in BC from 1990 to 2021
  - Filename: “NumberOfFiresOverall.csv”

After the preliminary data analysis, we addressed the following potential climate change factors that could be correlated to the yearly number of forest fires in BC. 
- Area Burned in Hectares from Human Activity in BC from 1990 to 2020
  - Filename: “HumanActivityFiresModified.csv” 
- Atmospheric CO<sub>2</sub> Levels from 1990 to 2021
  - Filename: “co2.csv”
- Canada's CO<sub>2</sub> Emissions from 1990 to 2016
  - Filename: “CanCO2Data.csv”
- Prince George Precipitation Levels from 1998 to 2022
  - Filename: “precipdata.csv”
  
We looked for significant positive correlations between yearly global carbon dioxide emissions in Canada, yearly atmospheric CO<sub>2</sub> levels and yearly Prince George precipitation levels, to the yearly number of hectares burned by wildfires in BC. 
To conduct these analyses we computed linear regressions between each data set and plotted the results. To understand potential results we looked to the $R^{2}$ values to address potential correlations and the p-value to demonstrate significance.
## Preliminary Data Analysis
### Total Number of Fires from Human Activity in BC from 1990 to 2021
![image](https://github.com/user-attachments/assets/9cf94972-165d-418e-892d-1e54301125a8)

Human Activity Fires Outcome:
| $R^{2}$ |
| ------------- |
| 0.53 |

Key Findings
- Based on the $R^{2}$ value, the Anthropogenic Caused Fires CAN’T be significantly explained by a linear model as it can only predict 53% of the relationship between the Number of Fires and Years
- The total number of anthropogenic-caused fires is *decreasing* over time
### Total Number of Fires in BC from 1990 to 2021
![image](https://github.com/user-attachments/assets/0005342a-20e0-4c07-9013-5085d57a03f7)

Total Number of Fires Outcome:
| $R^{2}$ |
| ------------- |
| 0.19 |

Key Findings 
- Based on the $R^{2}$ value, the Total Number of Fires CAN’T be significantly explained by a linear model as it can only predict 19% of the relationship between the Number of Fires and Years
- The total number of fires in BC is *decreasing* over time

### Total Area Burned in Hectares in BC from 1990 to 2021
![image](https://github.com/user-attachments/assets/bc7dee85-b6e2-4b79-a6e9-c65029f62d58)

Total Number of Fires Outcome:
| $R^{2}$ |
| ------------- |
| 0.26 |

Key Findings:
- Based on the $R^{2}$ value, the Total Area Burned in Hectares in BC CAN’T be significantly explained by a linear model as it can only predict 26% of the relationship between the Total Hectares Burned and Years
- The total area of hectares burned in BC is *increasing* over time

## Climate Change Analysis
### Area Burned vs. Human Activity Fires in BC (1990-2020)
![image](https://github.com/user-attachments/assets/a23d0233-254d-4dde-b01f-8521bc7669a7)

Area Burned vs. Human Activity Fires Outcome:
| $R^{2}$ | P-Value|
| ------------- | ------------- |
| 0.0 | 0.17 |

Key Findings:
- Given that the P-value is 0.17, the linear regression model isn't considered statistically significant
- Given that the $R^{2}$ is 0, the linear regression model predicts 0% of the relationship between Area Burned and Human Activity Fires in BC
- Overall: Linear regression shows no significant correlation between the two variables.
### Atmospheric CO<sub>2</sub> vs Area Burned in BC (1990-2021)
![image](https://github.com/user-attachments/assets/3a1d53d0-2154-4eed-8878-84e96b10e144)

CO<sub>2</sub> vs Area Burned Outcome:
| $R^{2}$ | P-Value|
| ------------- | ------------- |
| 0.28 | 0.003 |

Key Findings:
- Given that the P-value is 0.003, the linear regression model is considered statistically significant
  - A p-value of 0.05 or lower is generally considered statistically significant.
- Given that the $R^{2}$ is 0.28, the linear regression model predicts 28% of the relationship between Atmospheric CO<sub>2</sub> vs Area Burned in BC
- Overall: Linear regression shows a significant correlation between the two variables with low model predictions.

### Area Burned in BC vs. Canada Fossil CO<sub>2</sub> Emissions (tons) (1990-2016)
![image](https://github.com/user-attachments/assets/bad9efe6-6d6a-4b07-bb37-8ff572bf4601)

Area Burned in BC vs. Canada Fossil CO<sub>2</sub> Emissions Outcome:
| $R^{2}$ | P-Value|
| ------------- | ------------- |
| 0.34 | 0 |

Key Findings:
- Given that the P-value is 0, the linear regression model implies that there is no linear relationship between Area Burned in BC and Canada Fossil CO<sub>2</sub> Emissions
- Given that the $R^{2}$ is 0.34, the linear regression model predicts 34% of the relationship between Area Burned in BC vs. Canada Fossil CO<sub>2</sub> Emissions
- Overall: Linear regression shows no significant correlation between the two variables.

### Annual Precipitation (mm) vs Area Burned (ha) in BC (1990-2021)
![image](https://github.com/user-attachments/assets/159254b1-65fc-448c-ac5e-dc9f2e9f7650)

Precipitation vs Area Burned Outcome:
| $R^{2}$ | P-Value|
| ------------- | ------------- |
| 0.13 | 0.03 |

Key Findings:
- Given that the P-value is 0.03, the linear regression model is considered statistically significant
  - A p-value of 0.05 or lower is generally considered statistically significant.
- Given that the R^2 is 0.13, the linear regression model predicts 13% of the relationship between Annual Precipitation (mm) vs Area Burned (ha) in BC
- Overall: Linear regression shows a significant correlation between the two variables with low model predictions.

## Summary of Results
1. Is the number of yearly human-caused fires across British Columbia, reported by the National Forestry Database, significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2020?
$\color{red}{\textsf{NO}}$
2. Is the yearly atmospheric carbon dioxide levels at Mauna Loa station significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2021?
$\color{red}{\textsf{NO}}$
3. Is Canada’s yearly carbon dioxide emission levels calculated by the Emission Database for Global Atmospheric Research​​ from fossil fuels significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2016?
$\color{red}{\textsf{NO}}$
4. Is the average yearly precipitation recorded at the Prince George weather station significantly positively correlated to the yearly number of hectares burned in British Columbia from 1990-2021?
$\color{red}{\textsf{NO}}$

## Discussion
- No statistically significant positive correlation between CO<sub>2</sub> levels, CO<sub>2</sub> emissions, precipitation levels, human activity and average annual hectares burned from forest fires in BC
- Limitations
  - Skew in the number of fires due to reporting errors
  - Using Prince George as a representative of the entire BC
  - Not being able to account for all variables influencing fires  
- Cannot conclude correlations between selected climate change variables and increase in hectares burned by forest fires in BC
- However, it is important to recognize the ongoing threat that forest fires pose to both local ecosystems in BC and the global environment:
  - Forest fires contribute to the acceleration of climate change by releasing greenhouse gases into the atmosphere 
  - Forest fires have devastating consequences for both surrounding communities and wildlife
  - There have recently been several devastating fire seasons 

## Conclusion
- The analyses performed did not yield a statistically significant positive correlation between forest fires and the climate change variables analyzed
- We must continue to address the various factors being influenced by climate change 
- There is a wide variety of possible variables that can impact forest fires 
- We must further investigate the potential reciprocal relationship between climate change and increased susceptibility to wildfire burning

## Bibliography
Canada, E. and C. C. (2023, April 14). Government of Canada. Canada.ca. Retrieved April 20, 2023, from https://www.canada.ca/en/environment-climate-change/services/environmental-indicators/greenhouse-gas-emissions.html  

Dr. Pieter Tans, NOAA/GML (gml.noaa.gov/ccgg/trends/) and Dr. Ralph Keeling, Scripps Institution of Oceanography (scrippsco2.ucsd.edu/)

National Forestry Database - Canadian Council of Forest Ministers (CCFM). (n.d.). Forest fires. Forest Fires | National Forestry Database. Retrieved March 8, 2023, from http://nfdp.ccfm.org/en/data/fires.php 

Total precipitation - annual data for prince george. Amateur Weather Statistics for Prince George, British Columbia. (n.d.). Retrieved April 20, 2023, from https://princegeorge.weatherstats.ca/charts/precipitation-yearly.html?fbclid=IwAR0F3u4AiX4MJbgzj7QBkYLOeDJlqlZkcYkUAYo-mC9y8NHx2ne4ZQrIoZ0   


