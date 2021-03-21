# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates ho received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
-Data source: election_results.csv
-Software: Python 3.9.2

## Summary
### Results
The analysis of the election shows that:
-There were 369,711 votes cast in the election.
-The candidates were:
  -Charles Casper Stockham
  -Diana DeGette
  -Raymon Anthony Doane)
  
-The candidate results were:
  -Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  -Diana Degette received 73.8% of the vote and 272,892 number of votes
  -Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
  
-The winner of the election was:
  -Diana Degette, who received 73.8% of the vote and 272,892 number of votes.
 
 ### Election-Audit Summary
 
 This code can be used for any election with a few modifications. This code works assuming that the second column in the file that it's reading is the county and the third 
 column is the candidate's name. However, we can modify the code to find which column contains the candidate's name by checking to see which column has a combination of blanks
 and characters since the county will be a single string.
 
 Also, this election simply takes a popular vote winner. In Canada, while each riding would be decided by the candidate who receives the most votes in that riding, parliament
 would give power to whichever party wins the most ridings. The US presidential election also uses a system similar to that where the winner of each state gets all of the 
 electors of that state, which implies that the overall popular vote winner may not be the winner of the election. To modify the code for this assignment, we would have to keep 
 a tally of which candidate is winning the most seats or states and not just the overall vote count of each candidate. 
 
 
