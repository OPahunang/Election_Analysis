# Election_Analysis

## Overview of Election Audit: 

A Colorado Board of Elections employee has given you the tasks to complete an audit of a recent local congressional election.

The project is to develop a Python script that enable to deliver the following information when the script is run:

   1.  Calculate the total number of votes cast

   2.  Get a complete list of county votes that:
        - Calculate the total number of votes per county
        - Calculate the percentage of votes per county

   3.  Get a report which county with the largest turnout 

   4.  Get a complete list of candidates who received votes that: 
        - Calculate the total number of votes each candidate received
        - Calculate the percentage of votes each candidate won

   5.  Determine the election candidate winner with total vote counts and percentage

   6.  Print the results to the command line and save to a txt file



## Election-Audit Results:

- In this election total of 369,711 votes cast

   Below is output screenshot of command Line and TXT file (election_analysis.txt)
   
         Command Line
   
   ![PyPoll_Challenge_Terminal_Output.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/PyPoll_Challenge_Terminal_Output.png)

         election_analysis.txt file
   
   ![PyPoll_Challenge_TXT_File_Output.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/PyPoll_Challenge_TXT_File_Output.png)


   Below is the screenshot of total votes including the script 
   
   ![Total_Votes_Count.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/Total_Votes_Count.png)


- Breakdown of the number of votes and the percentage of total votes for each county in the precinct, including the script

   ![County_votes_percentage.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/County_votes_percentage.png)


- County that had largest number of votes, including the script

   ![Largest_County_Turnout.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/Largest_County_Turnout.png)


- Breakdown of the number of votes and the percentage of the total votes each candidate received, including the script

   ![Candidate_votes_percentage.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/Candidate_votes_percentage.png)


- Candidate who won the election, with the total vote counts and total percentage, including script

   ![Winner_Candidate_vote_and_percentage.png](https://github.com/OPahunang/Election_Analysis/blob/main/Resources/Winner_Candidate_vote_and_percentage.png)



## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.63.2



## Election-Audit Summary:
The project successfully delivered Colorado Board of Elections requirements. It successfully summarized the total votes cast, provided complete list of counties with their respective total vote counts and percentage, provided complete list of candidates with their respective total votes counts and percentage, and provided who is the winner in the election. The generated report output - Visual Studio Code terminal and to a txt file named election_analysis.txt.

The developed script can be used for other county election without modification, only need an updated election_results.csv. It can also be used for state or country elections, with modification only of variable definitions for easy tracing of the developer who will modify it in the future.
