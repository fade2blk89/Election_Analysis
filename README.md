# Election_Analysis

## Project Overview
A Colorado Board of Elections employee, Tom, has tasked us with determining the winning candidate in a local congressional election, as well as providing the voter turnout for each of the 3 counties in the election. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.9, Visual Studio Code, 1.67.2

## Election Audit Results
- In this election, there were 369,711 votes cast among the 3 counties. 
- The breakdown of votes by county is as follows: 
  - Jefferson: 10.5% (38,855 votes)
  - Denver: 82.8% (306,055 votes)
  - Araphoe: 6.7% (24,801 votes)
- The county of Denver had the most votes with 306,055. 
- The candidates in the election were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockham received 23% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.  
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.      
- The winner of the election was: 
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.  

## Election Audit Summary

In summary, we believe this script can possibly be used to determine voter turnout in a statewide election. For example, the county_size and county_voter variables can be refactored as follows: 

state_size = 0
state_voter = 0
winning_percentage2 = 0

After setting these variables, the nested loop can be adjusted as follows: 

if (votes2 > state_size) and (statevote_percentage > winning_percentage2):
            state_size = votes2
            winning_percentage2 = statevote_percentage
            winning_state = states
            
In doing so, we will be able to maintain the accuracy for this script as it is modified for a larger or smaller data set.
