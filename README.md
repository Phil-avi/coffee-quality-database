# Coffee-Beans-Selection
This repo worked on the data and scrapping scripts provided by [jldbc](https://github.com/jldbc/coffee-quality-database) to acquire new coffee beans grading data from [Coffee Quality Institude](https://database.coffeeinstitute.org/login) .<br />

Various clustering models and random forest classification model were applied in order to identify the coffee beans that would potentially satisfy the whole Experian data scientist team.

# Data
These data contain reviews of 1438 arabica and 35 robusta coffee beans from the Coffee Quality Institute's trained reviewers. 129 newly scrapped arabica coffee beans' data was added to the orginal dataset.<br />

Robusta coffee beans were not considered in the analysis due to their nature of being bitter and stronger (which are the opposite of the team's preference)

# Environment
First, create a virtualenv or conda environment that includes the dependencies listed in the requirements.txt file. 

# Scrapping setup
To start scrapping, create a file name Credentials.py under the directory credentials. This file should contain valid login email and login password to Coffee Quality Institude website and your chromedrive address in order to use selenium. 
