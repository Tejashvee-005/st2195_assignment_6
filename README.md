# St2195_assignment_6
This repository contains my  R code for practice assignment 6.
# Task overview
Assignment 6 is about identifying common keywords among different pieces of news headlines and writing them into a csv file.
# What this code does
The code reads the data from the speeches file and relates it to EUR/USD exchange rate's performance. The EUR/USD exchange rate data is stored in the file fx.csv. Should exchange rate performance for a particular date be good, the code will look for words in the speeches given on that particular date that suggest that. The opposite is true for bad excahnge rate performance. The common good and bad indicators identified across the speeches are then stored in files good_indicators.csv and bad_indicators.csv. 
# Insights from running the relevant R code
Key takeaway= must call library(tokenisers)
The arguement for user defined function get_word_freq costed my self-esteem...
Apparently, it is required for the library(tokenisers) to be called. This may vary across machines, but my machine required it. 
