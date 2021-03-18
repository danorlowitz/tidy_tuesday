# TT_2021.03.16 Changelog

3/18

-   Decided to limit focus to Football Manager

-   Found Xin Yuen's [Farming Simulator entry](https://twitter.com/so_xinteresting/status/1372264924865499146), liberally borrowed her code for wrangling the data.

-   Realized that for some reason the dataset doesn't have anything for FM2013 or FM2019, womp womp

-   Set up a basic chart in ggplot showing the userbase of each game since release

-   Messed around w/ theme() to give it some color and have it vaguely resemble a soccer pitch

-   Added a second chart to show % of avg userbase vs. peak userbase

3/16

-   Created base file

-   Tried to convert avg_peak_perc to numerals

-   Spent the evening trying to figure out why mutate() wasn't working

-   Was taught on RD4S Slack that tt_load creates a list of frames, even if that list is 1 frame long, and that you have to load that frame for everything to work

-   Discovered that this dataset includes data from 2012 through 2021, not just 2021.
