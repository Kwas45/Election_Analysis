# ELECTION AUDIT & RESULTS


## Election Audit Overview

The purpose of this project is to provide election audit results to the elction commission highlighting total total votes, voter turnout for each county, percentage of votes from each county out of the total count, county with the highest turnout, and election results. The task assigned are as follows:

* >*Number of votes cast in the congressional election*
* >*Breakdown of the number of votes and the percentage of the total votes for each county in the precinct*
* >*County with the largest number of votes*
* >*Breakdown of the number of votes and the percentage of the total votes each candidate received*
* >*Candidate who won, their vote count, and the percentage of the total votes*


## Resources
Data Source [election_results.csv](https://github.com/Kwas45/Election_Analysis/blob/main/Resources/election_results.csv)

## Analysis
#### Summary
The below images show the election results printed to the terminal and also saved to the text file. Based on the data, the **total votes** were **369,711** **(100%)** with **Denver county** having the **largest number of votes** - **306,055** **(82.8%)** and Arapahoe county having the least - 24,801 (6.7%). With **272,892** **(73.8%)** votes, **Diana DeGette** won the elections and Raymon Anthony Doane had the least number of votes 11,606 (3.1%).

![Election results to terminal](https://user-images.githubusercontent.com/102786356/166120474-6b813e6f-d3fe-4465-8579-b96b6dcd27a0.png)
![election results to text file](https://user-images.githubusercontent.com/102786356/166120477-f212d77d-8d0f-4f81-babc-34e848ac4439.png)


##### 1. Total Votes
Total votes is initialized below, printed to the terminal and saved to the text file.   

![Initialize total vote](https://user-images.githubusercontent.com/102786356/166119664-181082a0-f682-4ee1-a78f-182166347361.png)
![total vote print to terminal and saved to text file](https://user-images.githubusercontent.com/102786356/166119681-cdfbf911-f214-4686-8321-a652a4b5abb4.png)


##### 2. County Votes and Percentages
To get the county results an if statement is written to check that the county does not match any existing count in the county list. A for loop is also initiated to get the county from the county dictionary. They results are printed to the terminal and saved to the file text. 

![county code ](https://user-images.githubusercontent.com/102786356/166120263-d9768980-87e2-4204-be37-f7fa53fd25d0.png)
![county percentage](https://user-images.githubusercontent.com/102786356/166120857-8c648edd-5d46-4697-ac0c-0a58a3539993.png)


##### 3. County with Largest number of votes


##### 4. Candidate Votes and Percentages
To get the candidate results an if statement is written to check that the candidate does not match any existing candidate in the candidate list. A for loop is also initiated to get the candidate from the candidate dictionary. They results are printed to the terminal and saved to the file text. 

![candidate if](https://user-images.githubusercontent.com/102786356/166121331-bb1b3e55-9ec5-4a07-a0b5-bae1bef3501a.png)
![candidate for](https://user-images.githubusercontent.com/102786356/166121334-80e31afd-9bec-4f2e-9b6a-c579c5f06110.png)

##### 5. Winning Candidate

