Polling Error
================
Ben Lee
11/12/2020

  - [Introduction](#introduction)
  - [How the polls performed in 2020 and
    2016.](#how-the-polls-performed-in-2020-and-2016.)
  - [Breakdown of the error across
    region](#breakdown-of-the-error-across-region)
  - [Pollsters do not catch the increase of GOP
    supporters](#pollsters-do-not-catch-the-increase-of-gop-supporters)
  - [Conclusion Remarks](#conclusion-remarks)

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

## How the polls performed in 2020 and 2016.

Below is a plot of how much do each parties outperform. The difference
between GOP’s vote share and its poll is drawn on x-axis whereas
Democrats’ is drawn on y-axis. If the source of error is the fundamental
uncertainty that exists in survey, the distribution of the error should
be scattered along the line of *y = -x* around (0,0). Ideally, it will
be along the diagonal line because when pollster overestimate one part
for 1%, it means that it underestimate the other party for 1%. And it
will centered around (0,0) because if error is random, the average of
the error should be zero.

However, Figure 1 shows it is not the case. All the data point is above
*y = -x* and the average of GOP and Democrat’s error in every states are
(4.28, -1.25), which means that Trump averagely outperform polling by
4.28% and Biden underperform polling by 1.25%.

![](PollingError_files/figure-gfm/poll%20error%202020-1.png)<!-- -->

| 2020 GOP Error | 2020 Democrat Error |
| -------------: | ------------------: |
|       4.280385 |          \-1.245385 |

In contrast, even though people criticized pollster for their
unsuccessful prediction on the election outcome in 2016, they performed
not as bad as how they did in 2020.

In 2016, while polling in some states underestimate the performance of
GOP, they overestimate GOP’s performance in others. In other words,
polling in 2016 behaves more like a random polling error than polling in
2020.

![](PollingError_files/figure-gfm/poll%20error%202016-1.png)<!-- -->

| 2016 GOP Error | 2016 Democrat Error |
| -------------: | ------------------: |
|       2.088462 |          \-1.348077 |

## Breakdown of the error across region

As we look deeper into how the polls erred in 2020, we can see the
errors looks quite differently across different regions in the U.S. In
figure 3, I breakdown the error of polls according to regions (as
defined by Bureau of Economic Analysis). It is noteworthy that the
extent to which poll deviate differs across regions. In Mideastern
Region (state such as New York, New Jersey and Penn) and Far West Region
(California, Alask, etc), the error looks more like random one than
systematic one, as the error for Democratic share of votes overlap with
the error of the GOP’s.

However, in regions such as Great Lakes and Rocky Mountain, the error
looks more like a systematic one, as the errors seem to correlated with
the party.

As we compare the regional breakdown of polling error in 2016, it is
clear that pollsters in 2020 behave worse than how they behave in 2016.
In 2016, errors are more random across different regions even though
there seems to be systematic error in Great Lake and Rocky Mountain
region.

By comparing how the errors look like in 2016 and 2020, we can see a
persistent trend in underestimating GOP supporters in Great Lake, Rocky
Mountain and Great Plain regions. This result suggest that polls perform
better in places where the lead pollster, such as WSJ, NYT, Ipsos, Pew,
etc, locate.

![](PollingError_files/figure-gfm/2020%20error%20regional%20plot-1.png)<!-- -->

![](PollingError_files/figure-gfm/2016%20erro%20regional%20plot-1.png)<!-- -->

## Pollsters do not catch the increase of GOP supporters

More importantly, not only do the pollsters get the numbers wrong, but
they also get the **trends** wrong. In Fig 5 and Fig.6, x-axis is the
poll changes between 2016 and 2020 and y-axis is the voteshare changes
between 2016 and 2020. While Fig.3 shows how pollsters fare for GOP,
Fig.4 shows how pollsters fare for Democrats.

In states where polling number for GOP decrease, majority of them
perform otherwise in the 2020 election. On the other hand, pollster get
the trend of Democratic voteshare right. In states where the polls
perform better in 2020 than in 2016, the vote share increases
accordingly.

![](PollingError_files/figure-gfm/republican%20change-1.png)<!-- -->

![](PollingError_files/figure-gfm/democrats%20change-1.png)<!-- -->

## Conclusion Remarks

This preliminary result points to the same issue: pollsters are having a
hard time getting GOP voters. The result also suggests that pollster
does not improve much on the weak spots. They claim to employ rigorous
stratification and weighting but it seems to be in vain. As we
[know](https://www.pewresearch.org/fact-tank/2019/02/27/response-rates-in-telephone-surveys-have-resumed-their-decline/),
the polling respond rate has dropped to ony **6%**, a rate which is
extremely hard for pollster to construct representative sample of the
population. Maybe what we need is some creative way of sampling such as
[using
Xbox](http://www.stat.columbia.edu/~gelman/research/published/high_frequency_polling.pdf).
