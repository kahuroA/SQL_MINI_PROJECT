# A STRATEGY TO WIN THE US ELECTIONS
The repository contains calculations done to identify the best strategy for a candidate to win the US elections. It takes into account the 51 states in America, the population and the Electors of each given state. The calculations are done using SQL to identify the best states to target so that the candidate can win the most electors and therefore win the election. 

PROJECT DESCRIPTION 

In the majority of countries in the world, winning the elections is a matter of winning the most number of votes. However in the US  this is different. To win the elections in America you have to win the most grand electors. Each of the 51 states have a number of grand electors. The grand electors are roughly but not exactly proportional to the size of the state meaning, that the larger states tend to have more grand electors than the smaller states. As other factors are used to determine the number of grand electors per capita, the size of the state is not always a determining factor of the number of electors the state has. To win the grand electors, the candidate has to win the popular vote in the state. The candidate who wins the state wins all the grand electors of that state and the runner up therefore receives 0 electors from that state. As data analysts we have been tasked with helping a candidate win the presidential election.

While doing the project, it is assumed that there are only two candidates and no there is no previous history such as certain states favouring a certain candidate or parties.

The project will answer which of the 51states should be prioritised to win the elections. The states are ranked by decreasing number of grand electors per capita. This will then help us identify which are the most valuable states. 

The steps that will be taken include:
-	joining the datasets;
-	ensuring that both datasets are the same format;
-	compute the ratio between the number of grand electors and the population;
-	order the states by decreasing ratio of Grand Electors per capita to identify the priority list; 
-	compute the running total for the grand Electors in the sorted list; 
-	compute the threshold of grand Electors needed to win the elections; and
-	Filter the list to identify the states needed to win the elections. 


TECHNOLOGIES USED 
SQLITE

USAGE 
This project advises on the best strategy for a candidate to win the US elections based on identifying the best states to target when campaigning as to increase the odds of winning. 

CONTRIBUTORS

1.	Antony Kahuro
2.	Catherine Gathoni
3.	Winnie Wanja
4.	Bella Juma
5.	Chris Ngige
6.	Desmond Nzioka
7.	Elvis Mwangi
8.	Joe Wambua
9.	Emmanuel Juma
