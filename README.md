# Python Challenge: Financial Analysis (PyBank) and Vote Counting (PyPoll)

## Introduction
In this challenge, you'll dive into Python scripting to analyze financial records and modernize the vote-counting process.
Before you begin, make sure to set up your environment by creating a new repository named python-challenge and organizing your files accordingly. The project consists of two main tasks: PyBank and PyPoll.
In the PyBank task, you'll analyze financial data from a dataset called budget_data.csv. Your goal is to calculate various financial metrics such as total months, net profit/loss, average change, and identify the greatest increase and decrease in profits.
In the PyPoll task, you'll work with election data from a dataset called election_data.csv. Your objective is to determine the total number of votes cast, list candidates who received votes, calculate their vote percentages, and declare the winner based on popular vote.

## PyBank Instructions
In this Challenge, you are tasked with creating a Python script to analyze the financial records of your company. You will be given a financial dataset called budget_data.csv. The dataset is composed of two columns: "Date" and "Profit/Losses".

Your task is to create a Python script that analyzes the records to calculate each of the following values:

The total number of months included in the dataset

The net total amount of "Profit/Losses" over the entire period

The changes in "Profit/Losses" over the entire period, and then the average of those changes

The greatest increase in profits (date and amount) over the entire period

The greatest decrease in profits (date and amount) over the entire period

Your analysis should align with the following results:

Financial Analysis
----------------------------
Total Months: 86
Total: $22564198
Average Change: $-8311.11
Greatest Increase in Profits: Aug-16 ($1862002)
Greatest Decrease in Profits: Feb-14 ($-1825558)
In addition, your final script should both print the analysis to the terminal and export a text file with the results.

# PyPoll Instructions
In this Challenge, you are tasked with helping a small, rural town modernize its vote-counting process.

You will be given a set of poll data called election_data.csv. The dataset is composed of three columns: "Voter ID", "County", and "Candidate". Your task is to create a Python script that analyzes the votes and calculates each of the following values:

The total number of votes cast

A complete list of candidates who received votes

The percentage of votes each candidate won

The total number of votes each candidate won

The winner of the election based on popular vote

Your analysis should align with the following results:

Election Results
-------------------------
Total Votes: 369711
-------------------------
Charles Casper Stockham: 23.049% (85213)
Diana DeGette: 73.812% (272892)
Raymon Anthony Doane: 3.139% (11606)
-------------------------
Winner: Diana DeGette
-------------------------
In addition, your final script should both print the analysis to the terminal and export a text file with the results.

## Hints and Considerations
-Consider what you've learned so far. You've learned how to import modules like csv. You’ve learned how to read and write files in various formats. You’ve learned how to store content in variables, lists, and dictionaries. You’ve learned how to iterate through basic data structures. And you’ve learned how to debug along the way. Using all that you've learned, try to break down your tasks into discrete mini-objectives.

-The datasets for these Challenges are quite large. This was done purposefully to showcase one of the limits of Excel-based analysis. As data analysts, our first instinct is often to go straight to Excel, but creating scripts in Python can provide us with more powerful options for handling big data.

Write one script for each of the provided datasets. Run each script separately to make sure that the code works for its respective dataset.
