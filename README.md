### bikesharing -> Module 14
# New York City Citi Bike Analysis

## NYC Citi Bike Overview
My client and friend Kate is interested in opening up bike rental kiosks in the Des Moines, Iowa.
Citi Bike rental data has been released to the public and Kate and I are able to use the data for our analysis using the Tableau application. 
We will need to be make sure we apply the data from NYC appropriately to Des Moines given the many differences including size of city, culteral and tourism rates.

Tableau was used to create 7 graphs that represent some of the data:
### 1. Checkout Times for Users
### 2. Checkout Times by Gender
### 3. Trips by Day and Hour
### 4. Trips by Gender by Day and Hour
### 5. User Trips by Gender and Day
### 6. Starting Location by Gender
### 7. Starting Location by User (Customer or Subscriber)


## NYC Bike Analysis Results
The analysis of the Citi data shows the following:
- Looking at all of the length of trips, even upon filtering variious amounts of time, most are under an hour. 
It may be worthwhile to investigate the price of rentals and if the rate could be decreased for additional hours of rental to understand this trend.

- To understand more about our riders we can look at the gender of our riders which only echos that of all riders.  There is not much difference between 
men and women accept that we can see men are definitely outnumber women as customers.

- In looking at the days of the week we can see that ridership increses during peak rush hours. 
On the weekend, as would be expected, riders use the bikes during the entire day.

- And the gender breakdown only echos this pattern. It is interesting that there seems to be a lull on Wednesday evenings.

- There are more subscribers than customers and we can see again that male outnumber females. There my be an opportunity to increase female ridership through marketing.

- To gain more knowledge of our base users, we can use the slider to navigate to each of the starting locations to see the number of male vs female at each location.

- As well, we can see who are subscribers vs customers per location.
![bikesharing](./CheckoutGender.png)
![bikesharing](./chkoutUser.png)

## Election-Audit Summary
This Python script was written to provide easy access to election results with-out needing to use excel which can be
more time consuming to run the process and to re-use available code.

Here are some possible additional uses for the module with somewhat easy modifications:
1) If the input .csv has additional columns or is not in the same order, it would be easy to modify the code to accept a different
.csv columnns.
2) If the election_results.csv could be modified to include if the ballots were either:
    - mail in
    - punchcard or machine counted
    - DRE computer counted cards
   Analysis could be completed to see which methods are used most often and even which counties utilize which methods the most.
3) It could be easily modified for primaries by using if and elif statements to get several of the candidates who received the top 
votes based on requirements of how many candidates are eligible to run.

# Challenge Overview

## Resources
- Data Source: election_resulrs.csv
- Software: Python 3.6.1, Visusal Studio Code, 1.38.1
