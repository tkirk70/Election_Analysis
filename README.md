# Election_Analysis
OSU Module 3 Python

## Project Overview
Complete audit of a Colorado election for a recent congressional seat. 

  1. Calculate total number of votes.
  2. Get a complete list of candidates who received votes.
  3. Calculate the total number of votes for each candidate and each county.
  4. Calculate the percentages for each candidate and each county.
  5. Determine the winner of the election based on the popular vote and the county with the highest voter turnout.

## Resources
  - [Data Source: election_results.csv](/Resources/election_results.csv)
  - Software: Python 3.8.8, PyCharm 2021.3 (Community Edition)

## Summary
[Election Results](/analysis/election_results.txt)
-------------------------
Total Votes: 369,711
-------------------------

### County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055) :+1:
- Arapahoe: 6.7% (24,801)
-------------------------
### Largest County Turnout:
  #### Denver
-------------------------
### Charles Casper Stockham:
  #### 23.0% (85,213)
### Diana DeGette:
  #### 73.8% (272,892) :+1:
### Raymon Anthony Doane:
  #### 3.1% (11,606)
-------------------------
### Winner:
  #### Diana DeGette
### Winning Vote Count:
  #### 272,892
### Winning Percentage:
  #### 73.8%
-------------------------

## Challange Overview
  The purpose of the election analysis audit was to process the results of the election without having to tabulate by hand.
  Results and summary were provided in one readable and one portable format.
  
## Challenge Summary
  This code can be used to tabulate election results for any jurisdiction.
  Modifications might include the types of files the election board is reading from and writing to.
  Modifications could be made to include a breakdown of candidate results per county.
  Voter turnout could be further calculated if population, voter registration, and eligible voters information were provided.
