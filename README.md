# Election Analysis

## Project Overview

### Purpose
Assisting a Colorado Board of Elections employee Tom in an election audit of the tabulated results for U.S. Congressional precinct in Colorado.  After Colorado Board of Elections counts the votes cast by three primary voting method, we will generate a vote count report including all following audit tasks to certify this U.S. congressional race. 

1.	Calculate the total number of votes cast.
2.	Get a complete list of counties in the precinct.
3.	Get a complete list of candidates who received votes.
4.	Calculate the voter turnout for each county.
5.	Calculate the total number of votes for each candidate.
6.	Calculate the percentage of voters from each county of the total count.
7.	Calculate the percentage of votes for each candidate.
8.	Determine the county with the highest turnout.
9.	Determine the winner of the election based on the popular vote

## Resources
- Data Source: election_results.cvs
- Software: Python 3.10.1, Visual Studio Code, 1.63.2

## Election Audit Results
The analysis of the election show that:

1. There were 369,711 votes cast in this congressional election.
2. Counties in the precinct were:
  - Arapahoe
  - Denver
  - Jefferson
3. The county results were:
  - Arapahoe 6.7% of the voter turnout and 24,801 number of votes.
  - Denver had 82.8% of the voter turnout and 306,055 number of votes.
  - Jefferson had 10.5% of the voter turnout and 38,855 number of votes.
4. The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
5. The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
6. The county with the highest turnout was:
  - Denver, which had 82.8% of the voter turnout and 306,055 number of votes.
7. The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

 ![image]()
## Election Audit Summary
This script is a way to automate the process of tabulating the election results. With one small modification - updating the dataset file path, it will be used to audit not only other congressional district but also senatorial districts and local elections. 

Moreover, it could be a handy tool for federal election as well. This will involve few more modification. For example, change the dataset file path, for better understanding we’d better change the variable names from county to state, and edit the print statement based on the audit requirements.    
