# Election Audit Analysis

## Project Overview
A Colorado Board of Elections employee has asked for an audit of a recent local congressional election. The following tasks were completed and described in the summary section: 

1. Calculation of the total number of votes cast.
2. Completed list of candidates who received votes.
3. Calculation of the total number of votes each candidate received.
4. Calculation of the percentage of votes each candidate won.
5. Determined the winner of the election based on popular vote.

## Resources
* Data source: [election_results.csv](https://github.com/cgurbatri/Election-Analysis/files/6447961/election_results.csv) located in Resources folder
* Software: Python version 3.8.2, Visual Studio Code 1.55.2

## Summary

The analysis of the election shows that: 
* There **369,711** were votes case in the election.
* The counties in the precint include: 
  **(1) Jefferson **
  **(2) Denver **
  **(3) Arapahoe **
* The votes (percentage of total votes, absolute vote count) per county were:
  **(1) Jefferson 10,5% (38,855) **
  **(2) Denver 82.8% (306,055)**
  **(3) Arapahoe 6.7% (24,801)**
* The county with the largest turnout was **Denver**.

* The candidates were: 
  **(1) Charles Casper Stockham**
  **(2) Diana Degette**
  **(3) Raymon Anthony Doanne**
* The votes (percentage of total votes, absolute vote count) per candidate were:
  **(1) Charles Casper Stockham 23.0% (85,213)**
  **(2) Diana Degette 73.8% (272,892)**
  **(3) Raymon Anthony Doanne 3.1% (11,606)**
* The winner of the election was **Diana Degette**. 

The above analysis can also be found in the following text file: [election_analysis.txt](https://github.com/cgurbatri/Election-Analysis/files/6448005/election_analysis.txt) in the Analysis folder. 

## Election- Audit Summary

This python script can be used to efficiently determine the vote count/percentage per county and candidate, county with the highest turnout, and more importantly the winner of the election. 

With modifications, this script can be used to determine which candidate was most successful in which county. This can be done by inserting another accumulator that counts votes per candidate per county. This could further provide insights into the political preferences for each county and inform campaign strategies. 

When applied to a more general data set with other features (such as voter demographic, state or city voting counts), this script could also be used to provide information about the age/gender of the voter per candidate. This could help inform campaign strategies regarding voter outreach per candidate. 


 
