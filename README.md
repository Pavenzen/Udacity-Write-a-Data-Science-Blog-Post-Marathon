# Udacity-Write-a-Data-Science-Blog-Post-Marathon
This is the repo to Write a Data Science Blog Post project for the Udacity Data Scientist Nanodegree Project about the Boston marathon results

1- Business Understanding

We investigated the Boston Marathon results from 2015,2016 and 2017 to find out what it takes for a 36 year old male to finish it.

For this we need to understand what are the important metrics to finsih the marathon in a certain time. 

For this, we asked 3 questions:

- How does the pace per age group developt over time? 
- Which age group has the biggest difference between the 1st and the 2nd half of the marathon?
- Can we predict the finish time by the halfway-point time?

2- Data Understanding

The data comes from Kaggel data set Finishers Boston Marathon 2015,2016 & 2017 by the User ROJOUR, the description taken from the Kaggle-page:

Content
It contains the name, age, gender, country, city and state (where available), times at 9 different stages of the race, expected time, finish time and pace, overall place, gender place and division place.
Decided to keep every year as a separate file, making it more manageable and easier to deal with it.

Link: https://www.kaggle.com/datasets/rojour/boston-results?resource=download

3- Prepare Data

For the data preparation phase, we gathered the data, assessed it and then proceeded to clean it, focusing on our columns of interest, with python libraries of Numpy, Pandas and re
We created a cleaning function which allows us too performe the identical operations on all datasets to asure the same structure 

4- Data Modeling

- For the 1st question I used a heatmap to visualize the different paces per age group over all 3 years.
- For the 2nd question I used grouped bar charts to visualize the time differences per year per age group
- For the 3rd question I used a random forst model on specific features to predict the finsih time and plotet the different charts to visualize the prediction

5- Evaluate the Results
For the Results, see either the notations inside the jupiter notebook or take a look at my blogpost: https://medium.com/@thomaspritzens/running-the-numbers-boston-marathon-2015-2017-through-the-lens-of-an-upcoming-data-scientist-8a1b3db3e8da

Finally, the readme format:

the libraries used: Numpy, Pandas, Matplotlib,Seaborn,re, sklearn,
the motivation for the project: as a upcoming marathon runner in munich on the 19-10-2024 I am alway interested in everything related to marathon runnig, and this data will probably help me set the perfect timetargets to finsih it. 
