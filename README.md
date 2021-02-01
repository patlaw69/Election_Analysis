# Election_Analysis-Colorado Congressional Audit

##Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a rencent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of the candiates who recived votes.
3. Calculate the total number of otes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

##Summary
The analysis of the election show that:
-There were "x" votes cast in the election.
-The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
-The candidate results were:
   -Charles Casper Stockham received "23%" of the vote and "85,213" number of votes.
   -Diana DeGette recieved "73.8%" of the vote and "272,892" number of votes.
   -Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
-The winner of the election was :
   -Diana DeGette, who received "73.8%" of the vote and "272,892" number of votes.
   
   ##Challenge Overview 
   The goal of this analysis was to find out the results of an election in Colorado
   ## Resources
- Data Source: election_results.csv
- Software: Python 3.9.1. Visual Studio Code, 1.52.1

   ##Election Audit Results
The analysis of the election show that:

There were 369,711 votes cast in the congressional election.

The table below shows the counties that participated in the election and the votes they contributed:

County:	Denver	Jefferson	Arapahoe
Votes:	272,892	38,855	11,606
Percentage:	73.8%	23.0%	6.7%
The county with the largest voter turnout was Denver.

The candidates were:

Charles Casper Stockham
Diana DeGette
Raymon Anthony Doane
The candidate results were:

Charles Casper Stockham recieved 23.0% of the final vote and 85,213 votes.
Diana DeGette recieved 73.8% of the final vote and 272,892 votes.
Raymon Anthony Doane recieved 3.1% of the final vote and 11,606 votes.
The winner of the election was

Diana DeGette recieved 73.8% of the final vote and 272,892 votes.
Election Audit Summary
In conclusion, this script may be used to audit results of future elections. While it was designed with this election in mind, small modifications can be applied to the script to work with any election. A few modifications are listed below:

In line 6 (shown below), "election_results.csv" would need to be changed to the name of the file containing the election data

file_to_load = os.path.join("Resources", "election_results.csv")
If the file contains different headers, lines 48 and 51 would need to be changed.

 candidate_name = row[2]
 county_name = row[1]
