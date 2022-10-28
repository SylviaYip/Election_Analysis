# Election Analysis
## Overview of Election Audit
A Colorado Board of Election has requested the following: the voter turnout for each county, percentage of voters from each county out of the total county, and the county with the highest turnout.  Python can be used to analyze the election data.  The requested information was provided by using for loops and conditional statements with membership and logical operators.
## Election-Audit Results
- A total of 369,711 were casted in the election. 
- List of counties:
    - Jefferson
    - Denver
    - Arapahoe
- County vote results:
    - Jefferson county received 38,855 votes (10.5% of total votes).
    - Denver county received 306,055 votes (82.8% of total votes).
    - Arapahoe county received 24,801 votes (6.7% of total votes).
- County with the largest number of votes:
    - Devener county received the most votes out of all of the counties with 306,055 votes (82.8% of total votes).
- List of candidates:
    - Charles Casper Stockham
    - Diana DeGette
    - Ramon Anythony Doanne
- Candidate results:
    - Charles Casper Stockham received 23.0% with 85,213 votes.
    - Diana Degette received 73.8% with 272,892 votes.
    - Raymon Anythony Doane received 3.1% with 11,606 votes.
- The winner of the election:
    - Diana Degette received 272,892 votes (73.8% of total votes).  As a result, Diana Degette won the election!

## Election-Audit Summary
The Python script used for this election can be applied to other elections.  The script can read and analyze the csv file's data.  The csv has three columns ("Ballot ID", "County", and "Candidate Voted for").  The script is able to create a dictionary where the candidate name is stored as a key and the number of votes received as a value.  Using the same methodology, the script can also determine the number of votes from each county. Using for [loops](https://www.w3schools.com/python/python_for_loops.asp) can calculate the vote percentage for each candidate and voters per county.  This data ultimately determines the winner of the election!

For future elections, this script can also analyze additional data collected such as voter demographics such as age, sex, and ethnicity.  This extra data would be added as additional columns into the csv file, and the script would be able to do to the calculations through repetition statements for more analysis and print the results to a text file.  As a result, this could provide valuable insight on what type of voters are voting for each candidate.

In addition, this script can also view the election results depending on what year is chosen.  A [print statement](https://realpython.com/python-print/) can be added in the beginning to ask the user "What year's results would you like to see?" and the user can input the year (ex: 2022).  This can be a very useful to see the results from different years!

All in all, Python is a very powerful tool for data analysis and there are many ways to futher modify the base code!

