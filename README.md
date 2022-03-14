# Election_Analysis
Module 3

## Project Overview
A congressional election took place in Colorado and Seth and Tom, employees on the Board of Elections, asked for help on the voting results. I used Python 3.9.7 on VS Code along with the voting results on an Excel file.

## Results

### The data we needed to retrieve.
1. The total number of votes cast:

![Screen Shot 2022-03-14 at 7 08 32 PM](https://user-images.githubusercontent.com/98489681/158275327-c28f77bb-8751-4320-ad6b-4ff89a4ecc0c.png)

This total was found simply by counting the amount of rows in the dataset, election_results.csv.

2. A complete list of candidates who recieved votes and the amount and percentage of votes each candidate won:

![Screen Shot 2022-03-14 at 7 09 17 PM](https://user-images.githubusercontent.com/98489681/158275361-dbbf1407-470f-47e7-89f0-138dcb4133b1.png)

Below is the code that summarized the candidate results with names, votes, and percentage of votes:
![Screen Shot 2022-03-14 at 7 12 35 PM](https://user-images.githubusercontent.com/98489681/158275699-87d0acbd-8d81-43ac-86ea-4377796a8f3c.png)

3. The winner of the election based on popular vote.   

![Screen Shot 2022-03-14 at 7 14 48 PM](https://user-images.githubusercontent.com/98489681/158275906-514652de-957b-4fd0-8a9b-18e0ac1b4b91.png)

Below is the code written for the winner of the election. We extracted this data from the previous code of candidate results. 

![Screen Shot 2022-03-14 at 7 15 24 PM](https://user-images.githubusercontent.com/98489681/158276060-3c809c47-0000-46f1-8d70-6e1eea3a4a50.png)


## Summary

Below is the collection of the final results:

![Screen Shot 2022-03-08 at 7 20 58 PM](https://user-images.githubusercontent.com/98489681/157353808-bded06e6-10f3-4e80-a4fb-620450a78968.png)

### Election-Audit Proposal:
I would like to continue to provide analytics to the election commision with this code. Now that the code is written, it will be very simple to use for future elections. We can change the city, candidates, amount of candidates, and more. For the future, we could also add in info on how each candidate was fundraising or campaigning to bring about knowledge for what may tend to be more useful in strategizing. We could also add in household info or the dates the voters went to vote to give further insight on the demographics. This could lead to learning more about cities and how to generate a better turnout, with accesible means for all.
