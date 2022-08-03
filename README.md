# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has assigned me the job of completeing an election audit from a recent local congressional election
1. Calculate total number of votes cast.
2. Get a complete list of candidates who received votes
3. Calculate the total number of votes each candidate received
4. Calculate the percentage of votes each candidate won
5. Determine the winner of the election based on popular vote
## Resources
- Data Source: election_results.csv
- software: python 3.10 VS Code 1.38.1
## Summary
The Analysts of the election show that:
- There were 369,711 votes cast in the election
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
The candidate results were:
    - Charles Casper Stockham received 23.0% of the votes and 85,213 total number of votes
    - Diana DeGette received 73.8% of the votes and 272,892 total number of votes
    - Raymon Anthony Doane received 3.1% of the votes and 11,606 total number of votes
The winner of the election was:
    - Diana DeGette who received 73.8% of the votes and 272,892 total number of votes
## Challenge Overview
### Purpose
The purpose of this election audit was to find additional information like the voter turnout for each county, the percentage of votes from each county out of the total count, and find the county with the highest turnout.

### Election Outcomes:
![Screen Shot 2022-08-03 at 4 09 16 PM](https://user-images.githubusercontent.com/106174279/182721246-cf158991-5246-41bf-a6b5-237244b604de.png)

* How many votes were cast in this congressional election?
    - 369,711 total votes
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    * County Votes:
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)
* Which county had the largest number of votes?
    - Largest County Turnout: Denver
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    - Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%
## Challenge Summary
This script can be used for future elections with only a few modifications.
    1. By collecting election data in .csv form for the new county election, the file can simply be imported to the code in place of the current imported       .csv file
    2. If other aspects of the election want to be looked at, (ie. smallest county turnout), then the if statement under comment #6 would need to be            changed to have c_votes < county winner and county_vote_percentage<county_win_percentage.
