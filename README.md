# Recommendation with IBM

In this project,I Developed a recommendation engine based on user behavior and social network. Used Rank Based, User-User Based Collaborative Filtering and SVD Matrix Factorization to accomplish system

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>
This project is focusing on the interactions of articles and user who reads the article to provide a list of recommendations to the users by performing a data analysis on real data from the IBM Watson Studio platform. The main purpose of this project is finding the most suitable recommendations method as well as using svd method for predicting the user preference.


## File Descriptions <a name="files"></a>
There is a notebooks available here to showcase work related to the above questions.\
<br>
The notebooks contains my steps for making the recommendation for users/article readers based on the data analysis of the database provide within.\
<br>
In Ranks Based Recommendations,since we don't actually have ratings for whether a user liked an article or not, we used the interaction between user and article to identify their interest.\ 
<br>
In User-User Based Collaborative Filtering Recommendations, a function is used to reformat the df dataframe to be shaped with users as the rows and articles as the columns to find out the interaction relationship.\
<br>
Detail explanations are included to help  you walking throught process.

## Results<a name="results"></a>
The main findings of the code can be found inside the python notebooks.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
