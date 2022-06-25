# Election Audit
## Overview of the Election Audit
The names of the three candidates from the recent congressional election along with the number and percentage of votes received were provided to the election commission a short time ago.  These results also named the winner of the election. After receiving this information, the election commission requested the following additional information:
-	The voter turnout for each county.
-	The percentage of votes from each county out of the total number of votes, and
-	The county with the highest turnout.

These data have been compiled and are ready for the election’s commission review.

## Election-Audit Results
The summary of the results is as follows:
-	There were 369,711 votes cast.
-	The breakdown of votes by county was:

|County Name|Number of Votes|Percentage of Votes|
|----------------|--------------|---------------------|
|Arapahoe|24,801|6.7%|
|Denver[^1]|306,055|82.8%|
|Jefferson|38,855|10.5%|

- The breakdown of votes by candidate was:

|Candidate Name|Number of Votes|Percentage of Votes|
|----------------|--------------|---------------------|
|Dianna DeGette[^2]|272,892|73.8%|
|Raymon Anthony Doane|11,606|3.1%|
|Charles Casper Stockham|85213|23.0%|

## Future Use of the Script 
The script developed in Python for this audit can be easily adapted for election audits with some simply modifications.  A single report for various elected positions, from federal congressional to local city coucil, races can be housed in one report.  To accomplish this, an additional field will need to be added to the source data to capture the election type.  The script can also be adapted to show the results of ballot initiatives. This would involve changing the candidate portion of the report to reflect the nummber of for/against votes, which could then ultimately determine whether the ballot measure was successful.  Slight modifications would be required in the script to tally the results as a two-way decision rather than by candidate name. 

[^1]: County with the largest number of votes
[^2]: Winner of the election 


