# IEOR4501Project

Class: IEOR 4501\
Section: 001\
Group Members: David Zheng, Wendy Yu
Group Member UNIs: [dz2486, wy2390]


This IEOR 4501 group project is divided into two main parts and the code for the two parts are named Top10.ipynb and Parking.ipynb:

Part I: Given a dataset with 311 incident calls in New York City for the year 2020, we were asked to produce a Juypter notebook named Top10.ipynb that contained a variable "top10" that returns a Panda.Series. The Panda.Series returned should contain the top 10 causes ("Incident Type") of calls to 311 in our analyzed zip code area (10036). The Panda.Series should contain the name of the top 10 incident types (a string), the total number of these incident types in 2020, and sorted in descending order.

Part II: With the same given dataset and zip code in Part I, we were asked to produce another Jupyter notebook named Parking.ipynb that contained python code to determine whether "Illegal Parking" incidents were a larger fraction of total 311 calls in our selected zip code area (10036) than the fraction of Illegal Parking incidents to total 311 calls across all zip codes in NYC. This analysis is stored in a variable named "higher_parking_proportion" which contains a single bool value, True or False. If Illegal Parking was a higher proportion of total 311 calls in zip code area 10036 than across all zip codes, the variable should return "True", if not, then return "False".
