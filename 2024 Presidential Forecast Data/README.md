# 2024 Presidential Forecast Data
This folder contains the data from our [2024 Presidential Election Forecast](https://www.natesilver.net/p/nate-silver-2024-president-election-polls-model). We update these data whenever we update our forecast. 

## Polling averages
[`poll_average.csv`](https://github.com/eli-mckown-dawson/SilverBulletin/blob/main/2024%20Presidential%20Forecast%20Data/poll_average.csv) contains the polling averages for each day since 7/1/2024. It includes the following columns:
Column | Description
-------|------------
`state` | Name of the state <tr></tr> |
`modeldate` | Date of the model run <tr></tr> |
`candidate_name` | The candidate for this answer choice <tr></tr> |
`pct_estimate` | Polling average for the candidate listed in `candidate_name` on `modeldate` <tr></tr> |
`pct_trend_adjusted` | Trendline adjusted polling average for the candidate listed in `candidate_name` on `modeldate` <tr></tr> |
`display_average` | Indicator for whether there is enough polling to display the average for `state` on `modeldate` <tr></tr> |

## National topline
[`poll_average.csv`](https://github.com/eli-mckown-dawson/SilverBulletin/blob/main/2024%20Presidential%20Forecast%20Data/national_topline.csv) contains the national topline on each day since 7/29/24. It includes the following columns:
Column | Description
-------|------------
`modeldate` | Date of the model run <tr></tr> |
`candidate_inc` | Name of the incumbent <tr></tr> |
`candidate_chal` | Name of the challenger <tr></tr> |
`candidate_3rd` | Name of the third-party candidate <tr></tr> |
`ecwin_inc` | Chance that the incumbent will win a majority of the electoral votes <tr></tr> |
`ecwin_chal` | Chance that the challenger will win a majority of the electoral votes <tr></tr> |
`ecwin_3rd` | Chance that the third-party candidate will win a majority of the electoral votes <tr></tr> |
`ec_nomajority` | Chance that no candidate will win a majority of the electoral votes <tr></tr> |
`popwin_inc` | Chance that the incumbent will win the popular vote <tr></tr> |
`popwin_chal` | Chance that the challenger will win the popular vote <tr></tr> |
`popwin_3rd` | Chance that a third-party candidate will win the popular vote <tr></tr> |
`ev_inc`, `ev_inc_lo`, `ev_inc_hi` | Forecasted number of Electoral College votes for the incumbent, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`ev_chal`, `ev_chal_lo`, `ev_chal_hi` | Forecasted number of Electoral College votes for the challenger, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`ev_3rd`, `ev_3rd_lo`, `ev_3rd_hi` | Forecasted number of Electoral College votes for the third-party candidate, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`national_voteshare_inc`, `national_voteshare_inc_lo`, `national_voteshare_inc_hi`| Forecasted national vote share for the incumbent, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`national_voteshare_chal`, `national_voteshare_chal_lo`, `national_voteshare_chal_hi` | Forecasted national vote share for the challenger, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`national_voteshare_3rd`, `national_voteshare_3rd_lo`, `national_voteshare_3rd_hi` | Forecasted national vote share for the third-party candidate, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`nat_voteshare_other`, `nat_voteshare_other_lo`, `nat_voteshare_other_hi` | Forecasted national voter turnout based on past turnout, estimates of population growth, polls about whether voters are more or less enthusiastic about the election than usual and other factors in each state. Includes the upper and lower bounds of an 80% confidence interval <tr></tr> | 
`national_turnout`, `national_turnout_lo`, `national_turnout_hi` | Forecasted national voter turnout based on past turnout, estimates of population growth, polls about whether voters are more or less enthusiastic about the election than usual and other factors in each state. Includes the upper and lower bounds of an 80% confidence interval <tr></tr> |
