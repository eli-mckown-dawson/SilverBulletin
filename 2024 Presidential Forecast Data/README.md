# 2024 Presidential Forecast Data
This folder contains the data from our [2024 Presidential Election Forecast](https://www.natesilver.net/p/nate-silver-2024-president-election-polls-model). We update these data whenever we update our forecast. 

## Polling averages
`poll_average.csv` contains the polling averages for each day since 7/1/2024. It includes the following columns:
Column | Description
-------|------------
`state` | Name of the state
`modeldate` | Date of the model run 
`candidate_name` | The candidate for this answer choice
`pct_estimate` | Polling average for the candidate listed in `candidate_name` on `modeldate`
`pct_trend_adjusted` | Trendline adjusted polling average for the candidate listed in `candidate_name` on `modeldate`
`display_average` | Indicator for whether there is enough polling to display the average for `state` on `modeldate`
