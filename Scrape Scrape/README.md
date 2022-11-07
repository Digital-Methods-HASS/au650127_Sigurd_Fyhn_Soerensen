## Webscraping and analysis of homicide and police killing data

The goal of killedbypolice is to make readily available the data collected by the archvied version <http://killedbypolice.net/> for exploration, visualisation, and analysis.

We don't know much about who collected the data for <http://killedbypolice.net/>, or what their methods are. [FiveThirtyEight](https://fivethirtyeight.com/features/another-much-higher-count-of-police-homicides/) reported that he was 'an instructor on nonviolent physical-intervention techniques and that he prefers to remain anonymous'.

This is an important data set because the 'US government has no comprehensive record of the number of people killed by law enforcement.' ([*The Guardian*, 1 June 2015](https://www.theguardian.com/us-news/ng-interactive/2015/jun/01/about-the-counted)). The killedbypolice project is one of a few non-government projects that continuously collect data on police killings (see [Related work](#related-work) below).


## Acknowledgments
This repo extends Ben Marwick's work from 2018 in [KilledbyPolice](https://github.com/benmarwick/killedbypolice) by using webscraping tools of 2020 and by updating with data with records from 2019 and 2020.

## How to use
Start with
(1) scraping.Rmd, which teaches you
- how to scrape tables of data from the internet 
- create charts
- create maps (hexbins, grids) from the data
This script takes the archived killedbypolice.net database as input

