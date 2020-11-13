Polling Error
================
Ben Lee
11/12/2020

  - [Introduction](#introduction)
  - [How the polls performed in
    2020.](#how-the-polls-performed-in-2020.)
  - [Pollsters are having a hard time with Republican
    voters](#pollsters-are-having-a-hard-time-with-republican-voters)

## Introduction

As the election results from Florida came in around 7 o’clock in the
evening, one thing became clear: Democrat would not enjoy a landslide
victory as predicted by pollsters. Florida, a state where Biden led by
2.5% according to poll aggregator, did not show a positive result for
Biden. Even though 2.5% of lead in aggregate poll are definitedly within
the margin of error, Democrats were shocked by the margin GOP leads.
After the state was called for Trump, the final (uncertified) result
shows Trump won Florida by 3.4 percent. And Florida was not alone.

As the election results came in state by state, it seems not so much a
landslide as an uphill battle for Democrats. Wisconsin, Michigan and
Pennsylvania are called for Biden as the polls predicted, yet with a
much smaller margin of victory. Other Midwestern states such as Ohio and
Iowa, which showed a comfortable Biden lead before election, turned out
to be Trump strongholds. Everyone is asking: what goes wrong (again)?

Before all the data comes in and some analysis is conducted, we cannot
know the exact answer. And possibly we will never know the exact answer.
What I want to achieve here, is to see how off it is for pollster this
year compared with 2016’s. For the plots and analysis below, I use the
poll aggregated by
[FiveThirtyEight](https://projects.fivethirtyeight.com/polls/).
FiveThirtyEight gained its reputation in forecasting industry as it have
given a 29% winning change for Trump in 2016, while most other
forecasters gave Trump only about 5% of winning chance. FiveThirtyEight
relied heavily on polls to make forecast and have published weighted
polling result for the past four years.

## How the polls performed in 2020.

Below is a plot of how much do each parties outperform. The difference
between GOP’s vote share and its poll is drawn on x-axis whereas
Democrats’ is drawn on y-axis. If the source of error is the fundamental
uncertainty that exists in survey, the distribution of the error should
be scattered along the line of *y = -x* around (0,0). Ideally, it will
be along the diagonal line because when pollster overestimate one part
for 1%, it means that it underestimate the other party for 1%. And it
will centered around (0,0) because error should be random.

However,

| error\_r |   error\_d |
| -------: | ---------: |
| 4.280385 | \-1.245385 |

![](PollingError_files/figure-gfm/poll%20error%202020-1.png)<!-- -->

![](PollingError_files/figure-gfm/poll%20error%202016-1.png)<!-- -->

## Pollsters are having a hard time with Republican voters

![](PollingError_files/figure-gfm/republican%20change-1.png)<!-- -->

\#\#Pollster tends to get the change of Democrats Right

![](PollingError_files/figure-gfm/democrats%20change-1.png)<!-- -->

![](PollingError_files/figure-gfm/2020%20error%20regional%20plot-1.png)<!-- -->

![](PollingError_files/figure-gfm/2016%20erro%20regional%20plot-1.png)<!-- -->
