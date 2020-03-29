COVID-19 Growth Animation - U.S. States
================

The fight against COVID-19 in the United States is generally coordinated
and administered at the state level with the Federal government mainly
providing resources. As such, each state’s response to COVID-19 has
differed significantly from that of others.

This anmation, inspired by Aatish Bhatia’s version based on the [Johns
Hopkins Data](https://github.com/CSSEGISandData/COVID-19) at
<https://aatishb.com/covidtrends/>.

However, as Johns Hopkins has stopped tracking U.S. State-level data, I
instead am pulling that from the [COVID Tracking
Project](https://covidtracking.com/)’s very simple and easy-to-use API,
which provides a handy JSON download.

## Current Animation:

![](covid_growth_anim.gif)

<font size="2">*Last updated at 2020-03-29 09:20:53 MDT.*</font>

## Analysis

The main take away is that we’re all in this together.

As of March 27, only Washington State (WA) appears to have had any
significant impact on the COVID-19 growth rate.

## Code

  - `track_graph.R` is the primary script. It will output the gif.
  - Put in something here about the cron job.
