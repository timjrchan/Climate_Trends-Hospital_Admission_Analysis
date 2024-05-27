# GA-DSI-SG-42 Project 1

---

## Project 1: Exploring climate data of Singapore


---


## Problem Statement

Leverage climate data trends to optimize hospital resource allocation, including manpower and bed allocations, aiming to improve efficiency and patient care.




### Audience

Healthcare administrators working with/in hospitals.


## Summary

As the world is in the midst of climatic change, Singapore is experiencing increased frequencies of heavy rains and new record high temperatures. Our hospitals have experienced a surge in patients over the last years and more hospital beds are required. One of the several reasons a person can get inpatient care is getting in contact with a pathogen which causes the person to be infected. The endemic COVID-19 is a an example of an outbreak. Therefore, this project aims to analyse the Singapore's climate patterns from the year 1987 to 2022 and its relationship to hospital admissions. 




## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year| object | surface-air-temperature-monthly-mean | The year in YYYY format |
|month|object|surface-air-temperature-monthly-mean| The month in MM format |
|year_month|object|surface-air-temperature-monthly-mean| The year and month in YYYY-MM  format|
|mean_temp|float|surface-air-temperature-monthly-mean| Mean air temperature in Celcius|
|no_of_rainy_days| int64| rainfall-monthly-number-of-rain-days | Number of rainy days in a month|
|maximum_rainfall_in_a_day| float | rainfall-monthly-highest-daily-total | The highest rainfall in a day (mL)|
|total_rainfall|float|rainfall-monthly-total|Total rainfall in mm|
| mean_rh | float | relative-humidity-monthly-mean | Mean relative humidity in a month (%)|
| mean_sunshine_hrs | float | relative-humidity-monthly-mean | The amount of sunlight in a day (hrs)|
| ah | int | hospital2 | The number of patients admitted in a month fo Alexandra Hospital |
| cgh | int | hospital2 | The number of patients admitted in a month for Changi General Hospital|
| ktph | int | hospital2 | The number of patients admitted in a month for Khoo Teck Puat Hospital|
| nuh | int | hospital2 | The number of patients admitted in a month for National University Hospital|
| ntfgh | int | hospital2 | The number of patients admitted in a month for Ng Teng Fong General Hospital|
| skgh | int | hospital2 | The number of patients admitted in a month for SengKang General Hospital|
| sgh | int | hospital2 | The number of patients admitted in a month for Singapore General Hospital|
| tsh | int | hospital2 | The number of patients admitted in a month for Tan Tock Seng Hospital|
| cdc | int | hospital2 | The number of patients admitted in a month for Communicable Disease Centre|
| ncid | int | hospital2 | The number of patients admitted in a month National Centre for Infectious Diseases|
| imh | int | hospital2 | The number of patients admitted in a month for the Institute of Mental Health|
| kkh | int | hospital2 | The number of patients admitted in a month for Kandang Kerbau Women's and Children's Hospital|
| nhc | int | hospital2 | The number of patients admitted in a month for National Heart Centre|


## Datasets

[Total Monthly Rainfall](data/rainfall-monthly-total.csv) 

[Mean Monthly Relative Humidity](data/relative-humidity-monthly-mean.csv) 

[Mean Monthly Sunshine Duration](data/sunshine-duration-monthly-mean-daily-duration.csv) 

[Mean Monthly Air Temperature](data/surface-air-temperature-monthly-mean.csv) 

[Monthly Hospital Admissions](https://tablebuilder.singstat.gov.sg/table/TS/M870041) 

[Total Monthly Highest Rainfall](data/rainfall-monthly-highest-daily-total.csv) 

[Monthly Total Number of Rain Days](data/rainfall-monthly-number-of-rain-days.csv)


## Brief Summary

Singapore experiences tropical climated due to its position along the equator. Singapore do not have the typical seasons like the temperate regions but experiences moonsonal cycles. Singapore has high temperatures, an average rainfall of 171 rainy days a year, and have a humidity from 79 to 82%. There are many reasons why a person can get admitted and one of such reason is the understanding of relative humidity on the viability of the infections. This analysis have observed some form of a relationship betweeen relative humidity and hospital admissions through understanding of diseases and outbreaks. 


https://www.weather.gov/lmk/humidity

https://www.straitstimes.com/singapore/bed-crunch-at-singapore-hospitals-some-patients-are-stuck-in-emergency-departments

https://www.moh.gov.sg/docs/librariesprovider5/resources-statistics/reports/special_feature_sars.pdf

https://www.nea.gov.sg/dengue-zika/dengue/dengue-cases

https://www.ncbi.nlm.nih.gov/books/NBK222258/

Chan, K.-H. (2011). The Effects of Temperature and Relative Humidity on the Viability of the SARS Coronavirus. Advances in Virology, 2011, 734690. doi:10.1155/2011/734690 https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3265313/

Campbell, K. M., Lin, C. D., Iamsirithaworn, S., & Scott, T. W. (2013). The complex relationship between weather and dengue virus transmission in Thailand. The American Journal of Tropical Medicine and Hygiene, 89(6), 1183-1193.

The Effects of Temperature and Relative Humidity on the Viability of the SARS Coronavirus 
K.H.Chan, J. S. Malik Peiris, S. Y. Lam, L. L. M. Poon, K.Y.Yuen, and W.H. Seto (2011)


