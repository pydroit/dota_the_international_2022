## DOTA 2 The International 2022 Analysis
by Oluwatobi Ajao
##Background
The International is the vdeo game, Dota 2's annual esports world championship tournament hosted and produced by the game's developer Valve which has been held annually since 2011 (with the exception of 2020 due to the COVID-19 pandemic).

The International 2022 (#TI11) is the concluding tournament of the Dota Pro Circuit and the eleventh annual edition of The International which returns to Asia for the second time. The invite format is similar to the one used for the preceding International, whereby a point system based on official sponsored Regional Leagues and Majors will be used to determine the teams invited to The International.[source][source]

This analysis aims at giving insights into the TI11 event using different metrics to help us understand how the competition (and all within) fared.

## The Dataset
The opendota is an open source project for the Dota 2 community where Dota 2 data can be gotten for independent analysis. Data on Heroes, Matches, Players, Leagues and Teams can be gotten either through the:

API through which developers can build their applications, or the
Data Explorer where advanced queries can be run on PostgreSQL engine
For this analysis, both of these were used. Data was downloaded to csv through running queries on the Data Explorer, and requests were made to the api to generate data within this Jupyter Notebook.

The objective of this analysis is to examine activities around the TI11 league. There is about 8.5million price for the 1st place, so why not? With the available data, we will be examining matches played, top winning teams, heroes pick rate, heroes win rate, highest match duration, highest hero death per match, etc

## Some questions we can answer with the analysis

1. What are the top winning teams?
2. Which heroes have the highest pick rate?
3. Which heroes have the highest win rate?
4. What is the correlation between players'gold, gold per minute, xp per minute, tower damage and towers killed?
5. Is there a correlation between pick rate and win rate?
6. What matches have the highest duration?
7. Is there a correlation between duration and win rate?
8. Which teams have the highest kill on the average?
9. Which players have the highest kill average?
10. Which teams have the fewest deaths on the average?
11. Which players have the fewest deaths on the average?
