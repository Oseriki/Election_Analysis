# Election_Analysis

## Overview of Election Audit

The purpose of this project is to run the analysis of election results and generate the following outputs:

### Print candidate results to the command line showing (i) candidate total votes in the election, (ii) each candidate’s total votes and percentage and (iii) the winner of the election, winning count, and winning percentage of votes.

### Print county results to the command line showing (i) each county and its total votes count, (ii) each county and its percentage of total votes and (iii) the county with the largest number of voters.

### Save the above results to a text file

## Analysis and Results

### Analysis of Candidate Results

- Analysis of the election results csv file (https://raw.githubusercontent.com/Oseriki/Election_Analysis/main/Resources/election_results.csv) conducted using python analysis tool shows that three candidates contested in the congressional election and they are: Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. Also, the analysis shows that 369,711 total votes were casted. The candidate results and percentage of total vote for each candidates are as follows: 
	i. Charles Casper Stockham, 85,213 votes (23% of total votes)
	ii. Diana DeGette, 272,892 (73.8% of total votes)
	iii. Raymon Anthony Doane, 11,606 votes (3.1% of total votes)

- Based on this result, Diana DeGette is the winner of the election with 272,892 votes, representing 73.8% of total votes.

- See the following files supporting the above results: 
	i. A Python file labeled “PyPoll_Challenge.py in Election_Analysis repository for code that prints this result to the command line. Election_Analysis/PyPoll_Challenge.py at main · Oseriki/Election_Analysis (github.com)
	ii. A text file titled “election_analysis.txt” in the Analysis folder in the Election_Analysis repository showing the above results printed in a text file. Election_Analysis/analysis at main · Oseriki/Election_Analysis (github.com)

### Analysis of Candidate Results

- Analysis of the election results csv file (https://raw.githubusercontent.com/Oseriki/Election_Analysis/main/Resources/election_results.csv) conducted using python analysis tool shows that votes were casted in three counties namely; Jefferson county, Denver county, and Arapahoe county. 369,711 total votes were casted in all three counties and each county’s vote count and percentage of total vote are as follows: 
	i. Jefferson county, 38,855 votes (10.5% of total votes)
	ii. Denver county, 306,055 (82.8% of total votes)
	iii. Arapahoe county, 24,801 votes (6.7% of total votes)

- Based on this result, candidate Diana DeGette is the winner of the election after securing the largest percentage of total vote, 272,892 (73.8% of total votes)

- See the following files supporting the above results: 
	i. python file labeled “PyPoll_Challenge.py in Election_Analysis repository for code that prints this result to the command line. Election_Analysis/PyPoll_Challenge.py at main · Oseriki/Election_Analysis (github.com)
	ii. A text file titled “election_analysis.txt” in the Analysis folder in the Election_Analysis repository showing the above results printed in a text file. Election_Analysis/analysis at main · Oseriki/Election_Analysis (github.com)

## Election-Audit Summary

- The results reported in the previous sections of this analysis report  are the result of a thorough analysis of the election result conducted using Python analysis tool. The analysis shows that candidate Diana DeGette won the congressional election with 272,892, which represents 73.8% of total votes. Also, Denver county has the largest voters turnout with 306,055, representing 82.8% of total votes.

- The Python script used in this analysis can be used for any future elections with the following modifications:
	i. The current election results csv file used for the current analysis (see line 3 of the script) will have to be replaced with a new result file.
	ii. Column object labels will have to be modified to align with the order and position in the original data file. For example, in the current data file “county_name” is in the second column, hence, the code labeled “#3”, written as “county_name = row[1]” in the script, is used to extract the county_name data. This code will have to be modified for use in future elections if the county name data is in a different column. This should also apply to other objects (i.e., column labels) in future elections.   

