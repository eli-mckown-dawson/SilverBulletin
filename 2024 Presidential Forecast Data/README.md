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
[`national_topline.csv`](https://github.com/eli-mckown-dawson/SilverBulletin/blob/main/2024%20Presidential%20Forecast%20Data/national_topline.csv) contains the national topline on each day since 7/29/24. It includes the following columns:
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

## State toplines
[`state_topline.csv`](https://github.com/eli-mckown-dawson/SilverBulletin/blob/main/2024%20Presidential%20Forecast%20Data/state_topline.csv) contains the state-level topline results from our most recent model run. It includes the following columns:
Column | Description
-------|------------
`modeldate` | Date of the model run <tr></tr> |
`candidate_inc` | Name of the incumbent <tr></tr> |
`candidate_chal` | Name of the challenger <tr></tr> |
`candidate_3rd` | Name of the third-party candidate <tr></tr> |
`state` | Name of the state <tr></tr> |
`tipping` | Tipping-point chance, the chance the state will deliver the decisive vote in the Electoral College <tr></tr> |
`vpi` | Voter power index, the relative likelihood that an individual voter in the state will determine the Electoral College winner <tr></tr> |
`winstate_inc` | Chance the incumbent will win the state <tr></tr> |
`winstate_chal` | Chance the challenger will win the state <tr></tr> |
`winstate_3rd` | Chance the third-party candidate will win the state <tr></tr> |
`voteshare_inc`, `voteshare_inc_lo`, `voteshare_inc_hi` | Forecasted vote share for the incumbent, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`voteshare_chal`, `voteshare_chal_lo`, `voteshare_chal_hi` | Forecasted vote share for the challenger, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`voteshare_3rd`, `voteshare_3rd_lo`, `voteshare_3rd_hi` | Forecasted vote share for the third-party candidate, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`voteshare_other`, `voteshare_other_lo`, `voteshare_other_hi` | Forecasted vote share for other candidates, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`margin`, `margin_lo`, `margin_hi` | Forecasted margin for the incumbent, including the upper and lower bounds of an 80% confidence interval <tr></tr> |
`win_EC_if_win_state_inc` | Chance that the incumbent will win the Electoral College if they win this state <tr></tr> |
`win_EC_if_win_state_chal` | Chance that the challenger will win the Electoral College if they win this state <tr></tr> |
`win_state_if_win_EC_inc` | Chance that the incumbent will win this state if they win the Electoral College <tr></tr> |
`win_state_if_win_EC_chal` | Chance that the challenger will win this state if they win the Electoral College <tr></tr> |
`state_turnout`, `state_turnout_hi`, `state_turnout_lo` | Forecasted state-level voter turnout based on past turnout, estimates of population growth, polls about whether voters are more or less enthusiastic about the election than usual and other factors in each state. Includes the upper and lower bounds of an 80% confidence interval <tr></tr> |

## Presidential polls
[`pres_pollist.csv`](https://github.com/eli-mckown-dawson/SilverBulletin/blob/main/2024%20Presidential%20Forecast%20Data/pres_pollist.csv) contains an entry for each poll, and how much the model adjusts each poll for the house and trendline adjustments. It includes the following columns:
Column | Description
-------|------------
`modeldate` | Date of the model run <tr></tr> |
`state` | Name of the state <tr></tr> |
`candidate_name` | The candidate for this answer choice <tr></tr> |
`startdate` | The first day interviews were conducted for this poll <tr></tr> |
`enddate` | The last day interviews were conducted for this poll <tr></tr> |
`pollster` | The name of the pollster <tr></tr> |
`samplesize` | The size of the sample <tr></tr> |
`population` | Whether the population interviewed was adults, registered voters, or likely voters <tr></tr> |
`weight` | A relative weight that describes how much this poll factors into the forecast relative to other polls <tr></tr> |
`influence` | A relative weight that describes how much this poll factors into today's the forecast (similar to "weight", but also takes into account how old the poll is) <tr></tr> |
`pct` | Voteshare for this candidate in this poll <tr></tr> |
`house_adjusted_pct` | Voteshare in this poll after applying the house adjustment <tr></tr> |
`trend_and_house_adjusted_pct` | Voteshare in this poll after applying both house and trendline adjustments <tr></tr> |
`tracking` | Whether or not the poll sample overlaps with other polls in our database <tr></tr> |
`poll_id` | Unique identifier for a poll <tr></tr> |
`question_id` | Unique identifier for a question <tr></tr> |
