# predictive modeling of number of rides per bike station per day

## possible variables *(and thoughts about variables):*
- trip duration *(some stations may be more prone to have shorter rides)*
- station id *(certain locations may be more popular)*
- large events in Pittsburgh/Oakland *(may be a manual process of creating this dataset; large events assume higher ride share use)*
- daily weather *(percent precipitation and temperature may affect ride share use)*
- average grade within half a mile radius of station
- elevation of the station

## workflow:
- run predictive modeling for 2015 Q1 & Q3; 2016 Q2 & Q4, 2017 Q1 of number of rides per day at each station id to predict the daily rides per station in 2015 Q2 & Q4; 2016 Q1 & Q3; 2017 Q2
- rinse and repeat with different combinations of variables until produce a somewhat accurate predictive pattern
- with that mixture of variables, predict future rides in 2018