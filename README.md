<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Books Best Seller Analysis

*Data Analytics, June 2020, Berlin*

## Content
* [Project Description](https://github.com/MilVas/NSM_pancakes#project-description)
* [Question & Hypothesis](https://github.com/MilVas/NSM_pancakes#question--hypothesis)
* [Dataset](https://github.com/MilVas/NSM_pancakes#dataset)
* [Workflow](https://github.com/MilVas/NSM_pancakes#workflow)
* [Organization](https://github.com/MilVas/NSM_pancakes#organization)

## Project Description

Our project focuses on the best sellers, and compares the data from two sources: the list of best sellers published by New York Times and the list of the top viewed book pages on Wikipedia. 

## Question & Hypothesis

Although using the data from the US, The New York Times is one of the most prominent newspapers in the world, and their influence and audience go beyond the US territory. 

As written before, many people check the New York Times best seller list to make their decision on what book they want to buy next. Also people tend to search for the respective book on Wikipedia to get more information about the content.

Our assumption:
Given its influence, we assume that the New York Times list affects the search on Wikipedia; as a result, the majority of books on the chosen Wikipedia list (although including some of the books published centuries before the New York Times started publishing the list) should also be in the New York Times list.

Our question:
Can the New York Times data be correlated with the data on Wikipedia?

## Dataset

The dataset consists of two CSV files. 

The New York Times data was generated using their API (Link APII). Given the size of their data, we had to select one category, and we
decided to choose the combined published and e-books dataset (as opposed to, for example, hardcover best sellers list). This dataset
includes information about author, title, the month when each book was placed on their list, and the number of months it was on the list. 

The second CSV consists of the 30 top book pages on Wikipedia, according to the number of visits, and it includes the name of the book, its ranking on Wikipedia and the number of views (in million). This data was obtained through webscraping (Link Wikipedia table)

## Workflow

The workflow of our project was as follow:
* Gathering possible data sources while defining the topic
* Definition of questions that can be asked/topics that can be analyzed
* Extracting the data through API & web scraping
* Refine the questions that can be asked/topics that can be analyzed with regards to the extracted data
* Merging and cleaning data
* Thinking about the potential analysis that could be conducted on the generated dataset. 
* Preparing presentation based on our insights
* Finalizing folder and file structure

## Organization

For communication we mainly used:

* Zoom
* Slack

For the definition of the topic and the remaining tasks we used:

* Google Docs (was used for brainstorming and thinking about questions for the research)
* GitHub repository

Our workflow was fluid, and depended on our pace and complexity of each task. 

