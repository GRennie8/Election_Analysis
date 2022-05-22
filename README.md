# Election Analysis Challenge

## Purpose of Election Audit

The purpose of this challenge was to assist Tom audit the US Congressional election in Colorado. During the module work, I was tasked with reporting:

    Total number of votes cast
  
    Total number of votes for each candidate
  
    Percentage of votes for each candidate
  
    Winner of the election based on the popular vote.
  

For this challenge I was asked to report: 

    Voter turnout for each county
    
    Percentage of votes from each county out of the total county
    
    County with the highest turnout.

## Election Audit Results

 - **How many votes were cast in this congressional election?**
 
    There was a total of 369,711 votes cast in the congressional election

 - **Number of votes and the percentage of total votes for each county in the precinct.**
 
     - Denver was the county with the largest number of votes, with 82.8% of the popular vote. Reporting a total of 306,055 votes. 
     
     - Jefferson County received 10.5% of the popular vote or, 38,855 votes.
     
     - Arapahoe County received 6.7% with 24,801 votes.

        ![Screen Shot 2022-05-21 at 7 45 00 PM](https://user-images.githubusercontent.com/104115586/169674892-aa65c41f-cd32-4c8a-86f8-5eeddeddcb19.png)


 
 - **Number of votes and the percentage of the total votes each candidate received.**

     - The election was won by Diana DeGette, with 73.8% of the popular vote, and 272,892 votes.

     - Charles Casper Stockham received 23.0% of the vote, a total of 85,213 votes.
    
     - Raymon Anthony Doane received 3.1% of the vote, a total of 11,606 votes.

        ![Screen Shot 2022-05-21 at 6 12 15 PM](https://user-images.githubusercontent.com/104115586/169675183-6fefa7e1-7fa4-44a0-bbc9-b4bdb201bc08.png)       


## Election Audit Summary

In the election results .csv file there are 3 columns named "Ballot ID, County and Candidate Name". This script will count the number of times each county and candidate is in the list. These values can be different without needing to modify the script too much. This code will search through a specific column in the entire dataset. 1 = County. 2 = Candidate.

  ![Screen Shot 2022-05-21 at 10 12 58 PM](https://user-images.githubusercontent.com/104115586/169678318-cd5c38c8-0daa-4691-805a-8287c7208c4b.png)

This means we can easily audit federal elections and use State names in place of Counties.

This script can most certainly be used in any other election, provided you have the same number of columns within the .csv file. As you can see in the image below, the script allows for any election dataset to be used by changing the path from which the file is loaded.

   ![Screen Shot 2022-05-21 at 9 52 23 PM](https://user-images.githubusercontent.com/104115586/169677706-244d349b-9ac5-4a40-a3c6-381a617fa9e6.png). 
   
   
   Change "Resources" to the folder name and "election_results.csv" to your file name to load a different file.




