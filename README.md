# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.7, Visual Studio Code, 1.66.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The Candidate results were:
    - Charles Casper Stockham received 23.1% of the vote and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 votes.
- Votes in this precinct were gathered from the following counties:
    - Jefferson
    - Denver
    - Arapahoe
 - Voter turnout from each county are as follows:
    - Jefferson County had 38,855 votes cast contributing to 10.5% of the total votes.
    - Denver County had 306,055 votes cast contributing to 82.8% of the total votes.
    - Arapahoe County had 24,801 votes cast contributing to 6.7% of the total votes.
 - The county with the highest voter turnout was:
    - Denver County, which had 306,055 voters contributing to 82.8% of the total votes

## Challenge Overview
Congratulations are in order for Ms. Diana DeGette, the winner of this precinct's congressional election! Ms. DeGette won handily, accumulating nearly 3/4 of the total votes for this seat. Ms. DeGette was followed by Mr. Charles Casper Stockham and Mr. Raymon Anthony Doane, receiving 23.1% and 3.1% of the votes respectively. This contest proved not very exciting, as Ms. Degette received over 3 times as many votes as her nearest competitor.

Voter turnout analysis determined that Denver County easily had the most votes cast in this election. Denver County accounted for 82.8% of votes cast, followed by Jefferson County at 10.5% and Arapahoe County at 6.7%. One piece of data not provided that would be beneficial to analyze would be the number of registered voters in each county. With that information, we could see how many potential voters actually turned up to the polls for this election.

## Challenge Summary
Through the course of this audit, a Python script was developed in order to read data from a CSV file, perform calculations on that data, then write that data to a text file. This script was developed with flexibility in mind. Provided the layout for the data set input remains the same, this Python script can be used for any future election, no matter the number of candidates, counties, or voters.

However, two examples of modifications (moreso, "improvements") to this Python script are adviseable. First, as mentioned previously, I would recommend that the number of registered voters from each county be provided for audit. Just as the results above were determined, a simple mathematical statement could be added to the script to find the percentage of registered voters that showed up to the polls in a given election. A second example of how this script could be improved would be to include party affiliation with the provided voting information. Again, with a few simple statements added to the script, this data could show how voters of a particular party voted with respect to their selected candidate.

In summation, congratulations to Ms. Diana DeGette on being elected to this congressional seat! The voters of Colorado have overwhelmingly displayed their confidence in your abilities, and it is up to you to represent them to your fullest!

