# Election_Analysis

***Overview***

The purpose of this audit was to help Seth and Tom further their analysis of the election and find the *voter turnout for each county, percentage votes of the county compared to the total votes and the county with the highest turnout*. The idea was to have a clean code with proper indenting techniques and impeccable usage of the for loops and conditionals. 

***Election-Audit Results***

1. How many votes were cast in this congressional election?
  - After importing the dependencies and filing the path, the first order of business was to find the total number of votes cast for all the candidates. For this, a *for* loop       was added that iterated across each row and added +1 votes based on the name of the candidate. Inside the for loop an *if* conidition was used for the same. 
  
    ![image](https://user-images.githubusercontent.com/92342751/142747337-7431669f-58ae-4cac-b3e4-0a88e5b2f5df.png)

    An output code was added to save the results on text document.

    ![image](https://user-images.githubusercontent.com/92342751/142747349-5d843c88-691f-41b2-8845-a8fc86b4b7d8.png)

    The result was a pheneomenal **Total Votes of 369,711**

    ![image](https://user-images.githubusercontent.com/92342751/142747453-5a0a68f5-b449-4c24-b432-2a276789a0d2.png)

2. The next task was to provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct. For this, a *for* loop was added to get         each county from the dictionary of counties and then the percentage of votes for the county was calculated.

    ![image](https://user-images.githubusercontent.com/92342751/142747520-5b7de51f-261e-48ec-91ef-caa965fe3dd6.png)

    The result was printed to the output text file as below - 

    ![image](https://user-images.githubusercontent.com/92342751/142747558-67bb1a7d-b99f-49c4-94e7-d8732b152ff3.png)

3. The next task was to find out which county had the largest number of votes. A simple *if* loop did the trick as shown below - 

    ![image](https://user-images.githubusercontent.com/92342751/142747608-b9a2c01c-a080-4fb0-8245-bded3b04102d.png)

    The winning county was **Denver**

    ![image](https://user-images.githubusercontent.com/92342751/142747639-8a2ba1b4-866d-4702-9fc9-d49d7f33bb01.png)

4. The next task was to provide a breakdown of the number of votes for each candidate and the percentage of the total votes each candidate received. 

    ![image](https://user-images.githubusercontent.com/92342751/142747778-5c5fc6e7-e0a0-4cb5-a3c0-cd5d83d56d0f.png)

    The output was as shown below - 

    ![image](https://user-images.githubusercontent.com/92342751/142747715-efffcfbc-e5a0-42ac-8b6e-05a3dfb2f248.png)

5. The last task was to find which candidate won the election, what was their vote count, and what was their percentage of the total votes.

    ![image](https://user-images.githubusercontent.com/92342751/142747739-16d04391-6193-4672-ae2e-dcfb96f11b95.png)

    AND THE WINNER IS - **Diana DeGette** with a staggering vote count of **272,892**, thats **73.8%** of the total votes!!!!

    ![image](https://user-images.githubusercontent.com/92342751/142747829-a6fb1a0e-5b9c-4b7a-97d4-5c75ab0c9134.png)

***Summary***

This code is almost as generalised as it can get, however with a few modifications the code can be run for almost any election analysis. With another couple of conditionals and loops, the code can be modified to take into account the *gender of the voters*. This may help in determining which gender leaned more towards a certain candidate. This will be a good way to analyze as to what kind of campaigns works better with what section of the voters. 

The code can also be modified to make it an holistice nation-wide analysis and take into account the *various parties* the candidates fall under - Republican and Democrats. 



